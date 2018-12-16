# HTML Syntax
__Ensure you format your HTML elements validly by learning the parts that repeat consistently.__

Tags will differ, but the punctuation used to distiguish elements will mostly be the same. Refer to the following examples when writing new HTML code or when troubleshooting existing code.

## Punctuation symbols
`<` `=` `""` `>` ... `<` `/` `>`

## Broken out

|Opening tag|Attribute property|Attribute value|Content|Closing tag|
|:--:|:--:|:--:|:--:|:--:|
|`<a`|`href=`|`"https://journalism.cuny.org/">`|Newmark J School|`</a>`|
|`<iframe`|`src=`|`"https://www.youtube.com/embed/5xrxOQL-yrE">`|_n/a_|`</iframe>`|

Note that tags vary in the way they close out.

## End result
```html
<a href="https://journalism.cuny.org/">Newmark J School</a>
<iframe src="https://www.youtube.com/embed/5xrxOQL-yrE"></iframe>
```

# Syntax for writing HTML comments
```html
<!-- This is how to write a single-line HTML comment -->

<!--
This is how to write a
multi-line HTML comment
-->
```

##  Why comment throughout your code
Commenting your code is important for a number of reasons:
- It helps others who may work with you
- It helps others who may inherit your work
- It helps you recall why you made each decision in your code
- It helps you understand how code works

# Challenge
1. Omit any one of the symbols from a full element; resave the code file; then refresh the page in your browser. Try this again by omitting a different symbol. Note any ways that the web page becomes _broken_ and note how the browser interprets each omission.
2. Look up "HTML self closing tags"

---

Copyright &copy; 2018 by Malik Singleton. All rights reserved.
