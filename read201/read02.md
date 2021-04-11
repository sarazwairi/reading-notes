# Read: 02 - HTML Text, CSS Introduction, and basic JavaScript Introduction.

## HTML 

### Text 

The text is the contents of what displayed or presented on your website .

**The elements :**

Headings:
```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

Paragraphs:
```
<p>Paragraphs</p>
```

others:
```
<b>Bold</b>
<i>italic</i>
<sup>Superscript</sup>
<sub>Subscript</sub>
<strong></strong>
<em></em>
<blockquote> or <q>
<abbr>HTML</abbr>
<cite> , <dfn> , <address> , <ins> or <del> , <s>
```

### Introducing CSS

CSS help to construct rules that define how an element's content should be displayed, each element can manipulating using CSS;
height, width, font, size, style, color etc.....
To use ,use the selector and then use the declaration .
```
h1{
color: red;
background-color: #616161;
text-align: center;
padding-top: 20%;
}
```
multi-element :
```
main h1,
.text1,
.text2,
.text3 {
border: red 2px dashed;
}
```

Ways to use :
* Inline 
* Internal
* External ( best paractices)

## JavaScript 

### Basic JavaScript instruction

A script is a collection of one-by-one instractions.
A statement is a name given to each particular instruction.
A comment we use to to informed other developers how its works.

Online Comment 
```
//comment 
```
Multiple-Lines
```
/*
Multiple-Lines
*/
```
Variables in JS 
```
variable__keyword variable_name = variable_value;
```
`let` : variable keyword, numbers , stings and booleans.

Arrays : a unique kind of variable,for more than one value .
```
let color = new array('red', 'black', 'blue');
```
for all black color in array you need to know about index:
```
cosole.log("you choose color" + color[1]);
```
to change a value:
```
color[2] = 'white';
```
Operators you will assess a situation by cotrasting one of the script's characteristics with the desired outcome.

* `==` equal
* `!=` not equal
* `===` strict equal
* `!==` strict not equal
* `>` greater than
* `<` less than

logical operators ; true or false operators.
```
((5<2) && (2>=3)) 
```
do expression 1 & 2 they evaluate *expression 3*

**logical operators:**

* `&&` and
* `||` or
* `!` not

### Decisions and Loops

Loops to repeat a block of codes, types:

* `for`
* `while` 
* `do while`

All aloops have three characteristics:

* `var i = 0;`  initialization
* `i<10;`       condition
* `i++`         update


























































































































 