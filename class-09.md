## Forms `<form>`
There are several types of form controls that you can use to collect information from visitors to your site.
1. adding text =>Text input (single-line), Password input, Text area (multi-line)
2. making choices => Radio buttons, Checkboxes, Drop-down boxes
3. submitting forms => Submit buttons, Image buttons
4. uploading file => file upload

How Forms Work
1. A user *fills* in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received.
-  Information from a form is sent in name/value pairs.

## Lists, Tables & Forms
- list-style-type :It can be used on rules that apply to the `<ol>, <ul>, and <li>` elements. ` none disc circle square`
- to put as list`list-style-image:url(" ")`
- list-style-position : inside and outside.
> List Shorthand `list-style: inside circle;width: 300px;}`

## table properties :
- width 
padding
- text transform : to convert the content of the table headers to uppercase
- letter-spacing, font-size
- border-top, border-bottom
- text-align
- :hover : to highlight a table row when a user's mouse goes over it
- background-color.
for more informations [click here](https://eid-sukariah.github.io/readingnote/class-07)

## Styling Forms
Web Developer Toolbar: This helpful extension for Firefox and Chrome
provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML.
Download this tool from [here](https://chrispederick.com/%20work/web-developer%20To%20see%20the%20CSS%20styl)

## Events 
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events. 
**some type of event**
Event Name	Fired When
* error	    A resource failed to load.
* abort	     The loading of a resource has been aborted.
* load	   A resource and its dependent resources have finished loading.
* beforeunload	The window, the document and its resources are about to be unloaded.
* unload	The document or a dependent resource is being unloaded.

three steps involved in getting it to trigger some JavaScript code.
Together these steps are known as **event handling**.
1. Select t he element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response. 
3. State the code you want to run when the event occurs. 
