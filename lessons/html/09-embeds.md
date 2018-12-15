# Embedded content

You can use your web page to display content from an external resource from the web by _embedding_ it in what's called an "inline frame", or for short, `<iframe>`.

If you know the URL and dimensions and a few other particulars about the source material that you want to embed, then you can follow HTML syntax rules for the iframe tag and fill in details for the tag's attributes.

## Syntax
|Opening tag|Attribute property|Attribute value|Content|Closing tag|
|:--:|:--:|:--:|:--:|:--:|
|`<iframe`|`src=`|`"https://www.youtube.com/embed/5xrxOQL-yrE">`|_n/a_|`</iframe>`|

## Attributes
|Attribute property|Attribute value|Notes|
|:--:|:--:|:--|
|`allow`|...|Specifies a feature policy, such as `autoplay`, `fullscreen`, `geolocation`|
|`height`|`150`|The height of the frame in pixels. The default is 150.|
|`name=`|...|Used by the `target` attribute of HTML's `<a>`, `<form>`, or `<base>` tags; by the `formtarget` attribute of HTML's `<input>` or `<button>` tags; or the `windowName` parameter in JavaScript's `window.open()` method.|
|`src=`|`htts://...`|Full URL of the resource being embedded|
|`width`|`300`|The width of the frame in pixels or percentage. The default is 300 pixels.|

## Providers
Many online services, such as social media networks, that allow you to embed their content will likely provide the iframe code and might even allow you to customize that code for your purposes. Your task is to copy the code they provide and then paste it into any area of your web page that you designate.

## Challenge
1. Test all of the attributes of the iframe tag
2. Embed the following in your practice web page:
- A tweet
- An Instagram post
- A YouTube video
- Soundcloud audio
- A Google Maps example
- A Google Drive Slides presentation 
- A PDF
