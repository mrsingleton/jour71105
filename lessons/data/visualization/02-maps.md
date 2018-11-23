# Maps
tk

[Check out Mapbox Help](https://www.mapbox.com/studio-manual/help/)

The NYC Department of City Planning (DCP) website's OPEN DATA section gives the public access to map-friendly versions of the city's numerous political divisions, such as school districts, police precincts, community board zones, city council jurisdictions and more.

They offer this information in map-friendly file formats including "shapefiles" and "GeoJSON"

[DCP shapefiles downloads page](https://www1.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page)

Shapefiles can be read by certain software (ArcGIS, QGIS and others), yet GeoJSON can be read by the human eye (sort of).

## Example
These are the boundaries of NYC's five boroughs in GeoJSON form:

[Borough Boundaries](http://services5.arcgis.com/GfwWNkhOj9bNBqoJ/arcgis/rest/services/nybbwi/FeatureServer/0/query?where=1=1&outFields=*&outSR=4326&f=geojson)

What do think this information is?

Do a text search (Cmd+F) for _BoroName_

What patterns do you see?

Github can display GeoJSON files. Read "[Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github/)" for instructions and options.

## Walk through
Now get the GeoJSON for the School Districts

Save this file right from your browser:
- Select FILE » Save
- Name it "school-districts" or similar
- Be sure you use ".geojson" as its file extension

![](https://i.imgur.com/xTPhZJO.png)

NOTE: To ensure its file extension is .geojson: a) change its format to "All Files"; b) uncheck the "Hide extension" box; c) write its extension as .geojson (not .txt)


## Mapbox Studio

### How Mapbox Studio handles your data
To work with data in Mapbox Studio, you can either create a blank dataset to begin adding features to, or you can import existing data to edit.

NOTE: Mapbox Studio dataset editor can only display datasets of 20 MB or smaller

You can import either a `.csv` file or a `.geojson` file. However, if you use a CSV, you must ensure that its location data is already geocoded.

Typically, GeoJSON code is already properly formatted and is the recommended route when available.

Once you upload a GeoJSON file to Mapbox Studio, it reads and renders the "features" in each dataset's GeoJSON code. All JSON code is made up of _key/value pairs_ and each GeoJSON feature uses this same structure to pair elements that define the geographic information.

The basic format of GeoJSON code follows this format:

```geojson
{
    "id": "{feature_id}",
    "type": "Feature",
    "geometry": {
        "type": "Point",
        "coordinates": [
        40.75544,
        -73.9890067
        ]
    },
    "properties": {
        "name": "New York City"
    }
}
```

__Geometry__ defines a feature's `type` and also its lat/long `coordinates`. A geometry type can be a point, a line or a polygon.

__Properties__ list the things that describe the feature, such as its title and its description. This info is shown in popup boxes.

### To create a dataset
You don't need to _code_ GeoJSON directly. Instead, Mapbox Studio gives you a visual interface to manage your datasets while it automagically generates the underlying code.

To create a new dataset in Mapbox Studio:
- Create an empty dataset
- Use the drawing tools to add features to it (i.e. geometry and properties)

### To draw features
Use the DRAW tools to draw points, lines and polygons directly on the map or edit the geometry and properties of existing features.

### To search for places of interest
Use the search field in the toolbar to find a country, region, postcode, place, locality, neighborhood, address, etc. You will have the option to Save to dataset.

### To add style to your dataset in Mapbox Studio
While you can edit the GeoJSON code of a dataset in Mapbox Studio, only tilesets can be directly _styled_. So, once you finish editing your dataset's features, EXPORT it as a tileset and add it as a layer in Mapbox Studio's STYLE editor.

To style a dataset, follow these steps:
1. View your dataset.
2. Export it to a tileset.
3. Go to the Mapbox Studio style editor.
4. Add the new tileset as a layer.
5. Style away.

>Tilesets created through dataset export have a reference back to the original dataset... If you need to make further changes to your data, you can modify a dataset after you have exported to a tileset and re-export to have those changes reflected in the tileset. If you update a connected tileset, any styles that reference that tileset will also be updated automatically.


