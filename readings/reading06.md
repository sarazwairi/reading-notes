# Design Web Pages with CSS

Cascading Style Sheets (CSS) allows you to create rules that control how each element is presented. A css rule contain two parts: a selector and a declaration, which in turn consists of properties and values.

```CSS
p {
    font-family: Arial;}
```

To apply an external CSS to the HTML document, use the ```<link>``` element to indicate where to find the CSS file. It is an empty element which does not need a closing tag. It consists of three attributes:

- ```href``` which specifies the path to the CSS file

- ```type``` specifies the type of the document being linked to. The value should be ```text/css```

- ```rel``` which determines the relationship between the HTML page and the CSS file

Internal CSS can also be applied using ```<style>``` element inside the ```<head>```. The best practice is to use separate CSS file especially in multiple web pages.

## Colors

Colors in CSS can be represented in RGB values, hex codes, and color names of which there are 147 names supported by browsers.

CSS3 introduced different way to specify colors as HSL value which indicates hue, saturation, and lightness, with an additional opacity value.

## JavaScript Functions

A function is a series of statements grouped together to perform a specific task. The function name should indicate that task, which is important to **call** the function and execute it. The pieces of information passed to a function are called **parameters**. If the function is expected to yield an answer the result is called the **return value**.

Example of declaring a function:

```JavaScript
function sayHello(){
    document.write('Hello');
}
```

To call this function the following statement is used

```JavaScript
sayHello();
```

After the function is executed the code continues to run from where it was called. Functions can also take certain number of parameters, so when calling the function certain arguments, being either values or variables, are passed. To get a single value out of a function we use the return statement.

```JavaScript
function getArea(width, height){
    return width * height;
}
```

```JavaScript
getArea(2, 3);
```