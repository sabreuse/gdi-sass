# Intro to Sass

This is the Girl Develop It Intro to Sass course. Original materials by Catherine Farman, updated by Amy Hendrix, and based on <a href="https://github.com/girldevelopit/gdi-core-intermediate-html-css">Intermediate HTML/CSS materials</a> by Girl Develop It.

The course is meant to be taught in 2 two-hour sections. Each of the slides and practice files are customizable according to the needs of a given class or audience.

## Classes

### Class 1


#### Part 1: Introduction to Sass. What is it? Why does it matter?
We look at how Sass makes writing CSS easier, learn the basics of Sass syntax using SCSS, and set up our environment. You will install Sass, and get your files set up to compile Sass into CSS.

#### Part 2: Building Blocks of Sass.
You'll learn basic Sass concepts including variables, nesting, and color functions. Students will create a basic Sass stylesheet with color and font variables and nested styles for reusing CSS. 
You'll learn the difference between hidden comments and visible comments, and see the output of your Sass experiments.

### Class 2

#### Part 1: Sass Mix-Ins
You'll learn how to create mix-ins for reusable CSS, including CSS3 features like gradients, sprite images, and drop shadows. We'll redesign the front end of our site using Sass to style it with the latest CSS3 features.

#### Part 2: Custom Sass Functions
You will write your own functions to extend your Sass, using programming concepts like if/else statements, for loops, and lists to power your CSS.

#### Part 3: Sass Tips & Tricks
Sass extends CSS3, and there are also tools that extend Sass! We'll look at the following Sass helpers among others:
* [Compass](http://compass-style.org/), which gives you open source mix-ins and functions to use in your own code
* [CodeKit](http://incident57.com/codekit/) & [LiveReload](http://livereload.com/), applications for compiling Sass for your projects (without the command line)
* [Codepen.io](http://www.codepen.io) for sharing code a la JSFiddle

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
