# HTML Syntax
__Ensure you format your HTML elements validly by learning the parts that repeat consistently.__

Tags will differ, but the punctuation used to distiguish elements will mostly be the same. Refer to the following examples when writing new HTML code or when troubleshooting existing code.

### Punctuation symbols
`<` `=` `""` `>` ... `<` `/` `>`

### Broken down
|Opening tag|Attribute property|Attribute value|Content|Closing tag|
|:--:|:--:|:--:|:--:|:--:|
|`<a`|`href=`|`"https://ucr.fbi.gov/">`|FBI Uniform Crime Reporting|`</a>`|
|`<h2`|`class=`|`"subhead">`|Authorities investigating cause of incident|`</h2>`|

### End result
```html
<h1><a href="https://ucr.fbi.gov/">FBI Uniform Crime Reporting</a></h2>
<h2 class="subhead">Authorities investigating cause of incident</h2>
```

### HTML comment syntax
```html
<!-- This is how to write a single-line HTML comment -->

<!--
This is how to write a
multi-line HTML comment
-->
```
