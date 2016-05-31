# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
Explain here.
The Tag #1 pulls in an image.  Tag #2 is a is for a container in HTML that the CSS file can apply code to the entire container.

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here
The first one applies the background color to everything within the Div elements.  The one applies a style first then the uses the Div containers for that particular code.  The third one references another CSS style sheet to get the necessary page styling features.

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* This defines the div to input a radius of 50% around whatever is contained within the Div callouts in the HTML page. */
div {
  border-radius: 50%;
}

/* This is a Class indicator for all headers that have this callout .header p and establishes a font size of 18 pixels. */
.header p {
  font-size: 18px;
}

/* This is a Class indicator for all footers that have this callout .footer and give it an absolute coordinate positioning and establishes it at the bottomes. */

.footer {
  position: absolute;
  bottom: 0;
}


/* This is a Class indicator for all items with the callout .splash-image and pulls in and image from that location and covers the entire page with the image at 100% width. */

.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

/* This is a Class indicator with the callout .ninja:hover that acivates the clickable mouse when the cursor is over that particular element. */

.ninja:hover {
  display: none;
  color: black;
}
```

