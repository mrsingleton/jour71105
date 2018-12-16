# CSS Syntax
__Ensure you format your CSS rules validly by learning the parts that repeat consistently.__

Selectors will differ, but the punctuation used to distiguish properties and values will mostly be the same. Refer to these examples when writing new CSS code or when troubleshooting existing code.

### Punctuation symbols
All rules written in CSS have these marks in this exact same order all the time, every time. Even if you look at what seems to be complex CSS code -- for instance, here's [cuny.edu's stylesheet](http://www2.cuny.edu/wp-content/themes/cuny-mpt/style.css), you'll soon notice that all rules include these symbols in this format:  
`{` `:` `;` `}`

### Broken out
|Element Selector|Open Declaration|Property|Value|Close Declaration|
|:--:|:--:|:--:|:--:|:--:|
|`a`|`{`|`color:`|`#696;`|`}`|
|`.subhead`|`{`|`font-size:`|`14px;`|`}`|

### End result
```css
a {
  color: #696;
}

.subhead {
  font-size: 14px;
}
```

### Note on spacing
CSS doesn't pay attention to spaces or line breaks. Developers include spaces and line breaks just to make the code easily readable by fellow human beings, but the computer, the server, the web browser do not need all the extra spaces and line breaks. In fact, they process CSS much better and much faster when no spaces whatsover are present in the final version of the stylesheet, and there's even a name for that -- when all spaces are omitted from a stylesheet, it is said to be "minified". For instance, here's [the J School's actual stylesheet](https://www.journalism.cuny.edu/wp-content/themes/core/css/dist/master.min.css?ver=1.39.07.17.2018).

### CSS comment syntax
It is very important to include _comments_ throughout your CSS code. Use to comments to write special notes, specific information, odd caveats and reasons for making certain choices in your code. Comments help others who may work with you at a later time and they also help you recall how you've decided to code up your stylesheet.
```css
/* This is how to write a single-line CSS comment */

/*
This is how to write a
multi-line CSS comment
*/
```

---

Copyright &copy; 2018 by Malik Singleton. All rights reserved.
