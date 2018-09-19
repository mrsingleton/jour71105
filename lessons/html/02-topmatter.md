# Top Matter
HTML files include information at the beginning of the document that is hidden from the browser viewport but still detectable by search engines and scrapers. Only special HTML tags can be written into this area because it manages special rules and behavior.

## Broken out

`<!DOCTYPE html>` declares the version of HTML to the browser and helps browsers render the markup elements properly. This example declares HTML5, a simplified declaration compared to the format required for HTML 4:
>`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`

`<html>` part of the structure of the document and contains all subsequent tags. Its `lang` attribute helps accessibility screen readers determine the proper language to speak to users.

`<head>`

`<title>`

`<link>`

`<meta>`

`<script>`

`<style>`

## Full example
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Page Title</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="icon" type="image/png" href="http://example.com/myicon.png">
    <meta name="author" content="">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
```
