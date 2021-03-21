# jQuery, Events, and The DOM
![#](https://www.magesolution.com/blog/wp-content/uploads/2014/01/what-is-jquery-11.png)
**jQuery** is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility.

How to use it?
1.  include it in the html file by either using CDN or by installing the file and link.
2. Use CSS selector as parameter: `$()` as a shorthand for the `jQuery()`
3. add a method to selected element:`$(':header').addClass('headline');`

## jQuery objects
when you select element using jQuery, it stores a reference to the corresponding nodes in the DOM and you can store this references in jQuery objects inorder to wasly access them when you need them more than once.

## chaining 
The process of placing several methods in the same selector by using dot notation between the methods.
> the methods that retrieve information from the DOM cannot be chained.

## checking a page is ready to work with:
`A $( document ).ready() block.`
`$( document ).ready(function() {`
    `console.log( "ready!" );`
`});`
*short code*
`$(function() {`
    `console.log( "ready!" );`
`});`

updating content
`.html()` gives every element in the matched set the same new content.The new content may include HTML markup.
`.text()` gives every element in the matched set the same new text content. Any markup would be shown as text.
`.replaceWith()` replaces every element in a matched set with new content. It also returns the replaced elements.
`.remove()` removes all of the elements in the matched set.

insering elements
first create the new element by assigning it’s html code to a jQuery variable.`var $newltem = $('<li class="new">item</ li>');`.
then add the new element to the page using one of the following methods:
`.before()` inserts content before the selected element/s.
`.after()` inserts content after the selected element/s.
`.prepend()` inserts content inside the selected element/s, after the opening tag.
`.append()` inserts content inside the selected element/s, before the closing tag.

**working on attributes**
`.attr()` get or set a specified attribute and its value. to get the value of an attribute.
`.removeAttr()` removes a specified attribute (and its value).
`.addClass()` adds a new value to the existing value of the class attribute.

It does not overwrite existing values.
`.removeClass()` removes a value from the class attribute, without deleting the other values within the class attribute.

**working on css properties**
use the `.css ()` method to retrieve and set the values of CSS properties.

$('cssSelector').css({
'cssProperty1': 'value1',
'cssProperty2': 'value2'
});
**looping over selections**
use .each() method to perform statements on every item in the selection, you place these statements in a function and use that function as a parameter for the .each(). and you can refer to the selection with this or $(this) in the statements.

**adding event**
use the following syntax to add an event on an element: $(css-selector).on('eventName',theFunction())


