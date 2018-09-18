# Backgrounds
Control the background effect of an HTML page by following these steps

## Background color
CSS features a property that gives you direct control of the web page's backgound color, as well that background color of specific parts of the web page, i.e. block elements.

To control background color, decide which element you want to affect and then apply the `background-color` property to it. To change the background color of an entire web page, apply the rule to HTML's `<body>` element.

### Follow this syntax:

```css
body {
  background-color: #CCC;
  }
```

Alternatively, affect a specific HTML element, such as `<aside>` this way:

```css
aside {
  background-color: #EEF;
  }
```

## Background image
Similarly, CSS features another property that lets you display a background image to a web page or to a specific element of a web page.

Again, decide which element you want to affect and then apply the `background-image` property to it. Getting an image requires identifying its URL, so the CSS rule needs you to inclue an image files relative or absolute path.

### Follow this syntax:

```css
blockquote {
  background-image: url("https://i.imgur.com/HfAeBML.jpg");
  background-repeat: round;
  }
```

#### Note
The round value of the the background-repeat property forces the image to repeat and stretch to fill the space with no gaps.
