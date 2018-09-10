## HTML Element Syntax
Refer to these examples when writing new HTML code or when troubleshooting existing code.

|Opening tag|Attribute property|Attribute value|Content|Closing tag|
|:--:|:--:|:--:|:--:|:--:|
|`<a`|`href=`|`"https://ucr.fbi.gov/">`|FBI Uniform Crime Reporting|`</a>`|
|`<h2`|`class=`|`"subhead">`|Authorities investigating cause of incident|`</h2>`|

### Punctuation symbols
`<` `=` `""` `>` ... `<` `/` `>`

### End result
```html
<a href="https://ucr.fbi.gov/">FBI Uniform Crime Reporting</a>
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

---

## CSS Rule Syntax
Refer to these examples when writing new CSS code or when troubleshooting existing code.

|Element Selector|Open Declaration|Property|Value|Close Declaration|
|:--:|:--:|:--:|:--:|:--:|
|`a`|`{`|`color:`|`#696;`|`}`|
|`.subhead`|`{`|`font-size:`|`14px;`|`}`|

### Punctuation symbols
`{` `:` `;` `}`

### End result
```css
a {
  color: #696;
}

.subhead {
  font-size: 14px;
}
```

### CSS comment syntax
```css
/* This is how to write a single-line CSS comment */

/*
This is how to write a
multi-line CSS comment
*/
```
