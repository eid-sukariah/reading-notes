## CHART.JS
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

* setting up  from [here](https://github.com/chartjs/Chart.js)
* To **draw a line chart,** the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:
`<canvas id="  "width="150" height="150"></canvas>`
- The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts.
The first line in the script retrieves the node in the DOM representing the `<canvas>` element by calling the document.getElementById() method. Once you have the element node, you can access the drawing context using its `getContext()` method.
The script includes a function called `draw()`, which is executed once the page finishes loading; this is done by listening for the load event on the document. This function, or one like it, could also be called using window.`setTimeout()`, window.`setInterval()`, or any other event handler, as long as the page has been loaded first.

## colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use:
* fillStyle = color
Sets the style used when filling shapes.
strokeStyle = color
* Sets the style for shapes' outlines.

## Drawing text
The canvas rendering context provides two methods to render text:

* fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
* strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
- styling value: `font=value  textAlign=value  textBaseline=value  direction=value`
![color](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text/baselines.png)