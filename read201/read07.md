# Object-Oriented Programming, HTML Tables

## Domain Modeling

The content below is an excerpt from the article.

```
Summary:
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model 
that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.
```

# HTML AND CSS

## Tables

the content of the `<table>` are written out row by row `<tr>` .each cell of a table is represented using
a `<td>` element. at the end of each cell , you use a closing tag to end the table . fo more information on HTML table-building , see the
 HTML table builder. `<th>` is used just like the `<td>` element but its purpose is to represent a heading , spanning columns `colspan="2"` ,spanning rows `rowspan="2"`

`<thead>` the heading of the table should sit inside the `<thead>` element. `<tody>` the body should sit inside the `<tbody>` element. `<tfoot>` the footer belongs inside the `<tfoot>` element.

# JavaScript

## Functions , methods , and objects

A function is a named piece of code. it can be given data to work with ( in the form of parameters ) and can also return data.all data is expressly passed
to a function.

A method is a piece of code that is known by an object`s name .it should operate on data contained within a class.
an object on which a method is called is called is implicitly passed to it . a method is similar to a function in that it operates on data within the class.

Reference :
codefellows. "Codefellows/domain_modeling."GitHub , 2021,<https://github.com/codefellows/domain_modeling#domain-modeling>. accessed 17.04.2021
