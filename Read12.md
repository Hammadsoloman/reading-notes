# Read: 12 - Docs for the HTML <canvas> Element & Chart.js

**I Learned From This Chapter :**

* Charts are far better for displaying data visually than tables and have the added benefit that 
no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and
convey data quickly, but they’re not always easy to create.

* The great things about Chart.js are that it’s simple to use and really very flexible.

* At first sight a <canvas> looks like the <img> element, with the only clear difference being that
it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes,
width and height. These are both optional and can also be set using DOM properties. When no width and
height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 
The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size:
if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

* The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts
, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering
context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.

* Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists
of points connected by lines). All other shapes must be created by combining one or more paths.
Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency
, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

* measureText()
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.


