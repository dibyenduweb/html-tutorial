# Knowledge-hub
# HTML Cheatsheet

This cheatsheet provides a quick reference for HTML, covering basic to advanced concepts.

## Table of Contents

1. [Introduction](#introduction)
2. [Basic HTML Structure](#basic-html-structure)
3. [HTML Elements](#html-elements)
   - [Text Elements](#text-elements)
   - [Semantic Elements](#semantic-elements)
4. [Attributes](#attributes)
5. [Forms](#forms)
6. [Lists](#lists)
7. [Tables](#tables)
8. [Links](#links)
9. [Images](#images)
10. [Multimedia](#multimedia)
11. [Advanced HTML](#advanced-html)
   - [HTML5 Semantic Elements](#html5-semantic-elements)
   - [Web Forms 2.0](#web-forms-20)
   - [Responsive Web Design](#responsive-web-design)
   - [HTML5 APIs](#html5-apis)
12. [Best Practices](#best-practices)
13. [Resources](#resources)

## Introduction

HTML (HyperText Markup Language) is the standard markup language used to create web pages. It structures content on the web and is an essential skill for web developers.

## Basic HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Cheatsheet</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```
# html-elements

# text-elements
```html
<!-- Text Elements -->
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
<p>Paragraph</p>
<pre>Custom paragraph</pre>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<strong>Bold Text</strong>
<em>Italic Text</em>
<code>Code</code>
</body>
</html>
```
# semantic-elements
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>

<header>Header</header>
<nav>Navigation</nav>
<aside>Aside Content</aside>
<section>Section</section>
<article>Article</article>
<footer>Footer</footer>

</body>
</html>
```


# attributes
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
     
<a href="https://www.example.com" target="_blank">Link</a>
<img src="image.jpg" alt="Description">
<input type="text" placeholder="Enter text">


</body>
</html>
```

# forms
# To-do
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    <form action="/submit" method="post">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required>
    <input type="submit" value="Submit">
</form>

</body>
</html>
```
# lists
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    <ul>
    <li>Unordered List Item 1</li>
    <li>Unordered List Item 2</li>
</ul>

<ol>
    <li>Ordered List Item 1</li>
    <li>Ordered List Item 2</li>
</ol>

</body>
</html>
```
# tables
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    <table>
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </tbody>
</table>

</body>
</html>
```
# links
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    <a href="https://www.example.com">Visit Example</a>

</body>
</html>
```
# images
```html
<!DOCTYPE html>
<html lang="en">
<head>
   <title>HTML Cheatsheet</title>
</head>
<body>
    <img src="image.jpg" alt="Description">
</body>
</html>
```
# multimedia
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
   <audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio tag.
</audio>

<video width="320" height="240" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

</body>
</html>
```
# advanced-html
### HTML5 Semantic Elements
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    
<figure>
    <img src="image.jpg" alt="Description">
    <figcaption>Caption</figcaption>
</figure>

<mark>Highlighted Text</mark>
<progress value="70" max="100">70%</progress>
<time datetime="2024-01-04">January 4, 2024</time>

</body>
</html>
```
### web-forms-20
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    
<input type="color" value="#ff0000">
<input type="range" min="0" max="100" value="50">
<input type="date">
<input type="email">
<input type="number" min="1" max="10" step="1" value="5">

</body>
</html>
```

### responsive-web-design
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</body>
</html>
```

### html5-apis
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    <canvas id="myCanvas" width="200" height="100"></canvas>
<script>
    var canvas = document.getElementById("myCanvas");
    var ctx = canvas.getContext("2d");
    ctx.fillStyle = "#FF0000";
    ctx.fillRect(0, 0, 200, 100);
</script>


</body>
</html>
```


# best-practices
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Cheatsheet</title>
</head>
<body>
    
Best Practices
Use semantic HTML elements for better accessibility.
Optimize images for faster loading.
Keep code clean and well-organized.
Test your web pages across different browsers.
Resources
MDN Web Docs - HTML
W3Schools - HTML Tutorial

Feel free to customize and expand upon this template based on your specific needs.

</body>
</html>
```
