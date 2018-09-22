# Top Matter
HTML files include information at the beginning of the document that is hidden from the browser viewport but still detectable by search engines and scrapers. Only special HTML tags can be written into this area because it manages special rules and behavior.

## Broken out

`<!DOCTYPE html>` declares the version of HTML to the browser and helps browsers render the markup elements properly. This example declares HTML5, a simplified declaration compared to the format required for HTML 4:
>`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`

`<html>` part of the structure of the document and contains all subsequent tags. Its `lang` attribute helps accessibility screen readers determine the proper language to speak to users.

`<head>` starts the section of the document with informative data and links to related files.

`<title>` official title of document that gets read by search engines and scrapers (over what's included in the `<h1>` tag).

`<meta>` gives details about the document's content, info about info, data about data.

`<link>` integrates an external file with the HTML file. Typically used to connect to stylesheet files and to favicon images.

`<style>` used to test style rules in a single web page. Not a best practice to include when the HTML file is part of a multi-page website.

`<script>` integrates an external script file with the HTML file. used to connect to JavaScript files.

### Typical example
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Page Title</title>
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="author" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="icon" type="image/png" href="http://example.com/myicon.png">
</head>

<body>
```

## Connecting your HTML and CSS files
To ensure that your HTML documents respond to the rules written in your stylesheet file, you must "link" the documents by including a `<link>` tag reference in each HTML file's `<head>` component.

### Example
```html
<head>
  <link rel="stylesheet" href="styles/main.css" type="text/css">
</head>
```
Note that the location of the .css file must be specified.

## Challenge
1. Link a .css file from the same folder as your .html file.
2. Link a .css file from a _subfolder_ of your .html file's folder.
