# HTML Links, JS Functions, and Intro to CSS Layout

## HTML Links

Links allow you to move from one page to another.

### Types of Links

* one website to another
* page to page on same website
* one part of a page to another part of same page
* links that open an email addressed to someone

### Writing Links

 ```<a>href="http://www.google.com">GOOGLE<a/>```

## CSS layout

* elements group together sections of a page
* browsers will display pages with normal flow,but relative,absolute or fixed posititioning can be specified
* float property moves content to left or right of page
* pages can have a liquid or fixed layout
* keep pages within 960-100px wide and main concept in top 600px
* use grids for professional and flexible designs
* CSS frameworks make styling your page easier
* multiple CSS files can be included in one page

## Functions, Methods and Objects

### Functions

Are a series of statements grouped togother to perform a task

### Declaring a function using function keyword, function name and code block in curly braces

```function sayHello() {document.write('hello');}```

### Calling a function

```sayHello();```

### Declaring functions with parameters

```function getArea(width,height) {return width*height;}```

### Calling functions with arguments

```js
getArea(3,5);
wallWidth=3;
wallHeight=5;
getArea(wallWidth,wallHeight);
```

### Getting a single value from a function

```js
function calculationArea(width,height){var area=width*height;return area;}
var wallOne=calculationArea(3,5);
var wallTwo=calculationArea(8,5);
```

## Variable Scope

where can be used :

* global scope
* local scope

## Pair Programming

its a technique ,it helps progrmmers to scan codes for errors line by line and character by character.
there are two functions in par programming : the driver and the navigator.

there are 4 basic skilles that code fellows students should focus on them:

* Greater efficiency
* Engaged from feloow students
* Social skills
* Job interview readiness
