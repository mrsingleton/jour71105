# Maps
tk

The NYC Department of City Planning (DCP) website's OPEN DATA section gives the public access to map-friendly versions of the city's numerous political divisions, such as school districts, police precincts, community board zones, city council jurisdictions and more.

They offer this information in map-friendly file formats including "shapefiles" and "GeoJSON"

[DCP shapefiles downloads page](https://www1.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page)

Shapefiles can be read by certain software (ArcGIS, QGIS and others), yet GeoJSON can be read by the human eye (sort of).

## Example
These are the boundaries of NYC's five boroughs in GeoJSON form

[Borough Boundaries](http://services5.arcgis.com/GfwWNkhOj9bNBqoJ/arcgis/rest/services/nybbwi/FeatureServer/0/query?where=1=1&outFields=*&outSR=4326&f=geojson)

What do think this information is?

Do a text search (Cmd+F) for _BoroName_

What patterns do you see?

Now get the GeoJSON for the School Districts

Save this file right from your browser:
- Select FILE » Save
- Name it "school-districts" or similar
- Be sure you use ".geojson" as its file extension

![](https://i.imgur.com/xTPhZJO.png)

NOTE: To ensure its file extension is .geojson: a) change its format to "All Files"; b) uncheck the "Hide extension" box; c) write its extension as .geojson (not .txt)



