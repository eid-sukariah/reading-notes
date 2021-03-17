## RESPONSIVE WEB DESIGN and FLOATS
Responsive web design is the practice of building a website suitable to work on every device and every screen size

### Responsive vs. Adaptive vs. Mobile
![#](https://www.bluecorona.com/wp-content/uploads/2015/04/what-is-a-responsive-website.png)
**Responsive**: react quickly and positively to any change.
**Adaptive**: to be easily modified for a new purpose or situation.
**Mobile**: build a separate website commonly on a new domain solely for mobile users.

Responsive web design is broken down into three main components:

1. flexible layouts
building the layout of a website with a flexible grid, capable of dynamically resizing to any width by using relative length units (EX: percentages or em units)
**another new units:**
- vw: Viewports width
- vh: Viewports height
- vmin: Minimum of the viewport’s height and width
- vmax: Maximum of the viewport’s height and width
when the layout gets too small, or too large, text may become illegible and the layout may begin to break, in this case use media queries.

2. media queries
provide the ability to specify different styles for individual browser and device circumstances(the width of the viewport or device orientation for example)
> Logical Operators in Media Queries: *and, not, and only.*
`@media all and (min-width: 800px) and (max-width: 1024px) {...}`
selects all media types between 800 and 1024 pixels wide.

`@media not screen and (color) {...}`
 the expression applies to any device that does not have a color screen.

 `@media only screen and (orientation: portrait) {...}`
 only screens in a portrait orientation that have a user agent capable of rending media queries.

* Initializing Media Queries: there are three ways for using media queries:
1. using the @media rule inside of an existing style sheet.
2. importing a new style sheet using the @import rule.
3. linking to a separate style sheet from within the HTML document.
* Each media query may include a media type(all, screen, print, tv, and braille) followed by one or more expressions(when evaluates to true, the styles are applied)
1. media features that used in the expressions: height, width, resolution, orientation, aspect-ratio
**mobile first:** technique with using media queries, by using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows. it is useful since mobiles devices shouldn’t have to load the styles for a desktop.

Viewport
sometimes mobile devices cannot accees the viewport properties(width, height, scale, resolution) thus the media quere won’t activate. to solve that we use the `<meta>` in html or @viewport in css. the viewport properties: width (usually = device-width), scale (usually initial-scale=1); target-densitydpi (usually =device-dpi)


3. flexible media
As viewports begin to change size media(Images, videos, canvas,..) doesn’t always follow it. so you need to scale it by setting it’s max-width to 100% as the following img, video, canvas {max-width: 100%;}.




## Float 
is a CSS positioning property.
> we have much stronger tools for creating layout on web pages. Namely, *Flexbox* and *Grid*.
![#](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/web-text-wrap.png?resize=540%2C270&ssl=1)

to moves an element to Far right or far left of the Containing element use float property with left or right as a value.
![ image changes size the text in the box will reflow](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/reflow-example-1.png?resize=540%2C177&ssl=1)

* anything else inside the same Containing element will flow around the floated element
`syntax: float: right;`
* you can create a multi-coloum layout by using `<div>` element to represent each column then specify it’s width and margin(not necessary) and set it to float: left

### The Great Collapse
If a parent element contained only floated elements, the height of it would be zero which will affect the styling and might cause the elements to over flow. we fix that by clearing the float with additional techniques(like adding a div in the parent element with clear: both, or setting the overflow for the parent element to auto or hidden, or using the :after pseudo class to add a content with visibility:hidden)

### clearing the floats Float’s sister property 
using thenclear property it will prevent the element from moving up adjacent to the float like the float desires. it could have five possible values: both, left, right, none, inherit.