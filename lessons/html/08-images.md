# Images
A basic and key feature of a web page is the ability to display digital images. Just like web pages, which are files that have unique locations, images are files with unique _source_ locations that can be called into a web page by referencing their location.

## Syntax
|Opening tag|Attribute property|Attribute value|Closing tag|
|:--:|:--:|:--:|:--:|
|`<img`|`src=`|`"https://www.journalism.cuny.edu/wp-content/uploads/2017/05/latino_media_summit-miguel-paz-crop.jpg"`|`/>`|

## Example
```html
<img src="https://www.journalism.cuny.edu/wp-content/uploads/2017/05/latino_media_summit-miguel-paz-crop.jpg" />
```

Note that image elements are _self-closing_ and basically consider the source file as their content.

<img src="https://www.journalism.cuny.edu/wp-content/uploads/2017/05/latino_media_summit-miguel-paz-crop.jpg" width="50%" />

## Challenge
1. Use the image source above to adjust values for the `width` and `height` attributes to understand how image dimensions behave.
2. Use a few paragraphs of "[Lorem Ipsum](https://lipsum.com/)" dummy text to practice wrapping text around an image by using the `align` attrinute.
