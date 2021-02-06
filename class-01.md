**Browsers** People access websites using software called
**Web Servers** When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website.
**How the Web Works** When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.
**Tags** *HTML USES TAGS* act like containers. They tell you something about the information that lies between their opening and closing tags.
* opening tag `<p>`
* closing tag `</p>`

**Attributes** provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
`<img href="" targit="_blank">`
Here the attributes is(targit="_blank") 


*we can write comments in HTML e that will not be visible in the user's browser, you can add the text between `<!--  --!>`*

**ID attribute** Every HTML element can carry the id attribute it`s *globle attribute*. It is used to uniquely identify that element from other elements on the page.Its value should start with a letter or an underscore (not a number or any other character)

**Class attribute** The class attribute on any element can share the same value.Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. For example, you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites.

**inline element**
1. don`t add any break
2. don`t respect width & height
3. respect padding & margin {just left & right}

**block element**
1. take full width if no width
2. add line break
3. respect all margin padding width & height

`<div>`  allows you to group a set of elements together in one block-level box.you might create a `<div>` element to contain comments from visitors or  contain all of the elements for the header of your site (the logo and the navigation).

`<span>` It is used to  can control the appearance of the content of these elements using CSS. we use *id or class* in span : *To explain the purpose of this`<span>` element &
 So that CSS styles can be applied to elements that have specific values for these attributes

 `<iframe>` is like a little window that has been cut into your page and in that window you
can see another page attribute you need to know *src height width scrolling frameborder seamless*
 
 `<meta>` inside the `<head>` element and contains information about that web page.

 **Escape Characters** There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)
 |characters|code    |              
 |----------|--------|
 |      ©   |`&copy;`|
 |      &   |`&amp;` | 
 |      <   |`&lt;`  |
 |      >   |`&gt;`  |

