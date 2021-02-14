#  Document Object Model (DOM)

## hardest thing about writing code
* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable
- If understanding the problem domain is the hardest part of programming and you want to 
*  make programming easier, you can do one of two things:
* Make the problem domain easier
* Get better at understanding the problem domain
## Programming is easy if you understand the problem domain


## what is an object?
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
- variables become known as *properties* 
- functions become known as *methods*

The Document Object Model *DOM* specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

As a browser loads a web page, it creates a model of that page. The model is called a **DOM tree**, and it is stored in the browsers' memory. 
It consists of four main types of nodes. 
1. the document node :Every element, attribute, and piece of text in the
HTML is represented by its own DOM node.
2. ELEMENT NODES
HTML elements describe the structure of an HTML page. (The `<h l > - <h6>` elements describe what parts are headings; the `<p>` tags indicate where paragraphs of text start and finish; and so on.) To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is *why you start by learning methods* that allow you to access element nodes, before learning to access and alter text or attributes.

> Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser. 

3. Attribute nodes are not children of the element thar carries them; they are part of that element. Once you access an element, there are specific JavaScript methods and properties to read or change that element's attributes. For example, it is common to change the values of cl ass attributes to trigger new CSS rules that affect their presentation. 
4. Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rather a child of the containing element.

![DOM tree](https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-the-dom-tree/Image_6_DomTree.png) 

## working with the DOM tree :
Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 

## caching dom queries
methods to find an element more than once in the DOM, you should use a variable to store the result of this query.
jQuery cannot be used on elements until those elements are jQuery objects, which gives them access to the whole jQuery world. Enrobing them in the$() method turns them into jQuery objects on which you can call jQuery methods. Before that, they're simply elements in the DOM and won't respond to jQuery methods.
`getElementById()`
`querySelector()`
