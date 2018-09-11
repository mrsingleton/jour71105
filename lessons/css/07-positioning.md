# CSS Positioning

<hr>

**Sky0NWf_G**

Slides: [hackmd.io/p/Sky0NWf_G](https://hackmd.io/p/Sky0NWf_G)
Page: [hackmd.io/s/Sky0NWf_G](https://hackmd.io/s/Sky0NWf_G)

---

### HTML handles layout, but CSS Positioning gives you additional control over placement.

---

### CSS Positioning, in conjunction with jQuery events and effects, help you control _where_ interactivity occurs.

---

## Real World Examples

---

|New York Times|
|:--:|
|Jun 10 2016|
|[Tiny Home Test Drive](https://www.nytimes.com/2016/06/12/realestate/testing-the-first-micro-apartments-in-new-york-city.html)|
|by Penelope Green|
|_scroll down to "Outfitting a Very Small Apartment"_|

---

|EducationWeek|
|:--:|
|Jan 12 2015|
|[Classroom Noises That Can Distract Students](https://www.edweek.org/ew/section/multimedia/listen-classroom-noises-that-can-distract-students.html)|
|by Gina Tomko & Deanna Del Ciello|
|_use headphones or your computer's audio_|

---

## Positioning Types

1. Static _(default)_
2. Relative
3. Absolute
4. Fixed
5. Sticky

---

## Syntax

```css
img {
    position: relative;
}

div {
    position: absolute;
}
```

---

## How they work

- Placement effects
- Scrolling effects
- Layering effects

---

## How they're used

- Hotspots
- Nav bars
- Ad footers

---

## How they appear

![](https://i.imgur.com/o4vn4K0.png)

<small><em>Credit: <a href="https://internetingishard.com/html-and-css/advanced-positioning/" target="_blank">Interneting is Hard</a></em></small>

---

## How they appear

![](https://i.imgur.com/4UcDgRm.png)

---

_Be mindful of convenience vs annoyance_

---

## Exercise

Let's Make some hotspots

---

### Create an HTML web page

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    
  </body>
</html>
```

---

### Create a div

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div>

    </div>
  </body>
</html>
```

---

### Place an image within the div

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div>
      <img src="#" />
    </div>
  </body>
</html>
```

[_use this image_](https://mrsingleton.github.io/interactive/examples/positioning/images/lobby.jpg)

---

### Nest a new _child_ div

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div>
      <img src="lobby.jpg" />
      <div></div>
    </div>
  </body>
</html>
```

---

### Write "A" as text within the div

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div>
      <img src="lobby.jpg" />
      <div>A</div>
    </div>
  </body>
</html>
```

---

### Repeat to create div B

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div>
      <img src="lobby.jpg" />
      <div>A</div>
      <div>B</div>
    </div>
  </body>
</html>
```

---

How do you think this will look so far?

---

### Link to the stylesheet
- Save this HTML file as `position.html`
- Create a separate stylesheet
- Name it `position.css`
- Link to it within the HTML doc

```html
<head>  
 <link rel="stylesheet" type="text/css" href="position.css">  
</head>
```

---

### Also add the viewport line

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

### Let's verify what's happening so far

Enter this temporary rule into your stylesheet

```css
div {
  border: solid 3px #696;
}
```

---

_Delete that rule after you've viewed its effects in the browser_

---

### Give the parent div this class

```html
<div class="image-container">
```

---

### Give the child divs this class

```html
<div class="hotspot">
```

---

### Give child A this ID

```html
<div class="hotspot" id="spotA">A</div>
```

### Give child B this ID

```html
<div class="hotspot" id="spotB">B</div>
```

---

### Give the image this class

```html
<img src="lobby.jpg" class="hotimage" />
```

---

### Your HTML should look like this

```htmlmixed=
<html>
  <body>
    <h1>CSS Positioning</h1>
    <div class="image-container">
      <img src="lobby.jpg" class="hotimage" />
      <div class="hotspot" id="spotA">A</div>
      <div class="hotspot" id="spotB">B</div>
    </div>
  </body>
</html>
```

---

### Now let's jump into the stylesheet

---

### First, let's make the image fit

```css
.hotimage {
    width: 100%;
    height: auto;
}
```

---

### Check how it sizes in your browser

---

### Give the container div this rule

```css
.image-container {
    position: relative;
}
```

---

No visible change. Why?

---

### Let's ensure we control the container's size

```css
.image-container {
    position: relative;
    width: 100%;
    height: auto;
}
```

---

### Now it's time to make hotspots

How do you think this should work?

---

### What position type should we use?

Think back to what each one is meant for

---

Static?

Relative?

Fixed?

Sticky?

---

```css
.hotspot {
    position: absolute;
    }
```

---

### Most other styles are cosmetic

---

```css
.hotspot {
    position: absolute;
    width: 15px;
    height: 15px;
    text-align: center;
    padding: 10px;
    color: #666;
    background: #ccc;
    opacity: .6;
    font-family: sans-serif;
    font-weight: bold;
    outline: none;
    border: 2px solid #fff;
    }
```

---

### How does a square magically become a circle?

---

![](https://i.imgur.com/5Xl2Z4h.jpg)

---

```css
    border-radius: 100px;
```

---

### Now for the coordinates...

How does your browser handle all that space?

---

![](https://i.imgur.com/7NU0XJn.png)


---

### So how do you place the spot exactly where you want it to be?

---

```css
#spotA {
    top: ?;
    left: ?;
    }
```

---

### Try placing them accordingly

Hotspot A: Security Desk

Hotspot B: Waiting Area

<small><em>Play around. Make some guesses. Think it through. Try stuff out. Change it up. Talk it over. See what happens.</em></small>

---

### Compare Pixels vs Percentages

---

Here are my own best guesses

```css
#spotA {
    top: 55%;
    left: 20%;
    }

#spotB {
    top: 45%;
    left: 75%;
    }
```

---

[Here's what we're working toward...](https://mrsingleton.github.io/interactive/examples/positioning/)

[Here's the codepen (so far)...](https://codepen.io/mrsingleton/pen/YeRwaq/)

---

Build a diagram that shows how elements are positioned away from the top, left, bottom and right of the browser window by using this browser window code:


```htmlmixed=
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    font-family: Arial
}

* {
    box-sizing: border-box;
}

/* The browser window */
.container {
    border: 3px solid #f1f1f1;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
}

/* Container for columns and the top "toolbar" */
.row {
    padding: 10px;
    background: #f1f1f1;
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
}

/* Create three unequal columns that float next to each other */
.column {
    float: left;
}

.left {
    width: 15%;
}

.right {
    width: 10%;
}

.middle {
    width: 75%;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Three dots */
.dot {
    margin-top: 4px;
    height: 12px;
    width: 12px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;
}

/* Style the input field */
input[type=text] {
    width: 100%;
    border-radius: 3px;
    border: none;
    background-color: white;
    margin-top: -8px;
    height: 25px;
    color: #666;
    padding: 5px;
}

/* Three bars (hamburger menu) */
.bar {
    width: 17px;
    height: 3px;
    background-color: #aaa;
    margin: 3px 0;
    display: block;
}

/* Page content */
.content {
    padding: 10px;
}
</style>
</head>
<body>

<div class="container">
  <div class="row">
    <div class="column left">
      <span class="dot" style="background:#ED594A;"></span>
      <span class="dot" style="background:#FDD800;"></span>
      <span class="dot" style="background:#5AC05A;"></span>
    </div>
    <div class="column middle">
      <input type="text" value="cunyj.edu">
    </div>
    <div class="column right">
      <div style="float:right">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </div>
    </div>
  </div>

  <div class="content">
    <h3>Web Design</h3>
    <p>Your content here.</p>
  </div>
</div>

</body>
</html> 
```
