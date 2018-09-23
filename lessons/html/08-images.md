# Images
A basic and key feature of a web page is the ability to display digital images. Just like web pages, which are files that have unique locations, images are files with unique _source_ locations that can be called into a web page by referencing their location.

## Syntax
|Opening tag|Attribute property|Attribute value|Closing tag|
|:--:|:--:|:--:|:--:|
|`<img`|`src=`|`"https://i.imgur.com/uWBIxRe.jpg"`|`/>`|

## Example
```html
<figure><img src="https://i.imgur.com/uWBIxRe.jpg" /></figure>
```

Note that `<img>` is an _inline_ element, however, the `<figure>` element is a _block_ element so using the two together lets you work with images as blocks. 
Also note that image elements are _self-closing_ and they basically consider the source file as their content.

---

<figure><img src="https://i.imgur.com/uWBIxRe.jpg" width="75%" /></figure>

## Challenge
1. Use the image source above to adjust values for the `width` and `height` attributes to understand how image dimensions behave. First try pixel values, then try percent values.
2. Use the `<img>` element without the `<figure>` element. Instead, use it inline within a few paragraphs `<p>...</p>` of "[Lorem Ipsum](https://lipsum.com/)" dummy text to practice wrapping text around an image by using the `align` attribute.
