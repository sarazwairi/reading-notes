# Chart.js

chart.js is a javascript plugin that draws charts on the website using HTML5's canvas feature.its a well-documented plugin that makes creating bar charts,line charts,pie charts,and other types of graphs
a breeze.we'll make three diagrams to demonstrate how to use chart.js.

## Canvas API

### Basic usage of canvas

The canvas element is a canvas element.its simple to create any fallback content that will be shown
in older browsers that dont support it .fallbackcontent should still be available for those browsers
that dont support it .the material within the container would be ignored by browsers that accept canvas
and rendered normally.

### Drawing shapes with canvas

you would have understood how to draw rectangles,triangle , circles,arcs ,and curves by the end of this
essay.when drawing things onto the canvas ,working with paths is imprtant ,and we`ll show you how.

the grid we'll learn how to draw on a canvas in this tutorial. for this case , we`ll use the default canvas
grid. we can rotate and scale the grid, but we'll stay with the normal for now.the canvas feature has a width
of 150 pixels and a height of 150 pixels.the root of this grid is at coordinates in the top left corner(0,0)

Drawing rectangles unlike SVG,```<canvas>```only supports two primitive shapes:rectangles and paths(lists of points
connected by lines).all other shapes must be created by combining one or more paths.luckily, we have an assortment of
path drwaing functions which make it possible to compose very complex shapes.

### Applying styles and colors

different canvas choices available to us in order to make our drawings more appealing. you'll learn
how to enhance your sketches with various paints,line design, gradient, shapes , and shadows,
fillstyle and strokstyle are two essential properties that we can use . the fillstyle property
determines the fill style used when filling shapes.
strokestyle specifies the outline form for forms.color represents a CSS color, a gradient object, or
a pattern object as a string.

### Drawing text

the default font is a sans-serif font with a size of 10px.the font property is alson being used in
the exaples above to render the text bigger than the default size.there are a few more properties that
allow you to customize how the text appears on the canvas. if you`ve dealt with CSS before, you might be familiar
with these properties.
