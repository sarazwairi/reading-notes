# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

## HTML and CSS 

### lists

while creating a website you will like to use lists ,there are three categories of lists:
* ordered lists      `<ol>`
* unordered lists    `<ul>`
* definition lists   `<dl>`

`<li>` is an element that ordered and unordered lists use the description.

`<dl>` first element in the defeinition lists.
`<dt>` second.
`<dd>` third.

Examples:

Ordered lists: 
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Lists</title>
</head>

<body>
    <ol>
        <li>Ordered lists item 1</li>
        <li>Ordered lists item 2</li>
        <li>Ordered lists item 3</li>
    </ol>
</body>

</html>
```
Unordered lists:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Lists</title>
</head>

<body>
    <ul>
        <li>UnOrdered lists item 1</li>
        <li>UnOrdered lists item 2</li>
        <li>UnOrdered lists item 3</li>
    </ul>
</body>

</html>
```
Definition lists:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Lists</title>
</head>

<body>
    <dl>
        <dt>HTML & CSS</dt>
        <dd>Hypertext Markup Language (HTML)</dd>
        <dd>Cascading style sheets (CSS)</dd>
        <dt>JS</dt>
        <dd>JavaScript</dd>
     </dl>
</body>

</html>
```
list inside lists:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Lists</title>
</head>

<body>
    <ul>
        <li>UnOrdered lists 1 item 1</li>
        <li>
           <ol>
               <li>Ordered lists 2 item 2.1</li>
               <li>Ordered lists 2 item 2.2</li>
            </ol>
         </li>
         <li>UnOrdered lists 1 item 3</li>
    </ul>
</body>

</html>
```
BOXES

CSS file ```style.css```
```
p{
    border: blue 3px solid;
  }
```
HTML file``` index.html```
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Boxes</title>
    <link rel="stylesheet" href='/style.css'>
</head>

<boday>
     <p>SARA ZWAIRI</P>
     <P>RTNYU,JICEVRBTNYMU,IEXCRTVYNIMZ XCTOMZ RXCTRYUN VYBNEZ STRDYTFCUYVIGUBHOINAE ZSTRDXYTCFUYGBUHINz XCTVYUBYINU</P>
</body>

</html>
```
CSS file``` style.css```
```
p{
  width: 100px;
  height: 30px;
  background-color: #008080;
  }
```
The size of the text within the HTML file must be set ; the content inside the HTML  file can 
have a fixed size . to address this issue, you should use another declaration.


CSS file ```style.css```
 ```
p{
  min-width: 100px;
  min-height: 30px;
  background-color: #008080;
  }
```
OR

HTML file``` index.html```
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Boxes</title>
    <link rel="stylesheet" href='/style.css'>
</head>

<boday>
     <p>SARA ZWAIRI</P>
     <P>RTNYU,JICEVRBTNYMU,IEXCRTVYNIMZ fghjkl dfghjklxcvn,dfghjkl fghjk dfgh jXCTOMZ RXCTRYUN VYBNEZ STRDYTFCUYVIGUBHOINAE ZSTRDXYTCFUYGBUHINz XCTVYUBYINU</P>
</body>

</html>
```
If the block of text is greater than the box`s size:

CSS file ```style.css```
```
.description{
   width: 100px;
   height: 200px;
   background-color: #008080;
   overflow: scroll;
 }
```
HTML file``` index.html```
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Boxes</title>
    <link rel="stylesheet" href='/style.css'>
</head>

<boday>
     <P class="description">RTNYU,JICEVRBTNYMU,IEXCRTVYNIMZ fghjkl dfghextrcytvubyijnzxcryvubyinomxcyubnjkmxcyuinjokmxcryiobj kexctryubioin[mpwexrbyuiop,zrxctybhnjomkp dtufhvnrfdxgyuhjb ngcvx fgvn bgdv c6tgtub ntrfcv gvj bndf gyub ndf cgyhbjm erfdx chjb frdx cugyhjb ntgv ygbhj mggbhjf jklxcvn,dfghjkl fghjk dfgh jXCTOMZ RXCTRYUN VYBNEZ STRDYTFCUYVIGUBHOINAE ZSTRDXYTCFUYGBUHINz XCTVYUBYINU</P>
</body>

</html>
```

The border use to represent a concealed box around the element.
A margin is the space surrounding an element.
Padding is the space between an element and the material it contains.

border examples:
```
p{
   border-style: dotted;
}
```
```
p{
   border-style: dashed;
}
```
```
p{
   border-style: solid;
}
```
```
p{
   border-style: double;
}
```
```
p{
   border-style: groove;
}
```
```
p{
   border-style: ridge;
}
```
```
p{
   border-style: inset;
}
```
```
p{
   border-style: outset;
}
```

display :
```
p{
   display: inline;
}
```
hidden and visibility :the tag is not avlb, but room on the page has been set aside for it .
```disply: none;```   not visible but without take up space on the list.
```box-shadow  ```    creat a drop shadow around a box.
```border-radius ```  build rounded corners on any box.

## JavaSript 

# Basic JavaScript Instructions

Arrays is a variable for more than one value .

```let color = new Array('blue', 'red', 'black');```

to call red :

```cosole.log("you choose color "+color[1]);```

change black to white:

```color[2] = 'white';```

Descisions and Loops

If statement 
```
IF (condition)
{
   // block of code 
}
else if 
{
   //block of code
}
else 
{
   //block of code
}
```

Switch statement 

the awitch expression is only evaluated once, and its value is compared to the value in each instance.
```
switch(expression)
{
  case a:
     // code block
  case b:
     // code block
  break;
 default:
     // code block
}
```

Type of looping :

* for 
* while
* do while 

Characteristics of loops:
* ```var i = 0; ```   initialization
* ```i<10;```         condition
* ```i++```           update




























































 












































































































































































































































































































