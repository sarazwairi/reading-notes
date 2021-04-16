# Read: 06 - JS Object Literals; The DOM

FROM THE DUCKETT JS AND JQUERY BOOK

Chapter 3: " object literals"

What is an Object ?

* objects group together a set of variables and functions to create a model of something you would
 recognize from the real world . in an object , variables and functions take on new names.
* in an objet , variables become known as properties 
* in an object, functions becomes known as methods
* variables and named functions , properties and methods have a name and a value . in an object that 
 name is called a key

Chapter 5: " Document Object model"

* browser represents a page using a DOM tree
* DOM trees 4 types of nodes :
  * document nodes
  * element nodes
  * attibute nodes
  * text nodes

* can select element nodes by their id or class attributes,by tag name, or using CSS selector syntanx
* DOM query can return more than one node, it will always return a NodeList
* from an element node , you can access and update its content using properties such as textContent and
 innerHTML or usin DOM manipulation techniques
* an element node can contain multiple text nodes and child elements that are siblings of each other 
* browsers offer tools for viewing the DOM tree