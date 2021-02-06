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

**New Html5 Layout Elements** For a long time, web page authors used `<div>` elements to group together related elements on the page .now we use `<header> <footer> <aside> <article> <nav> <section>`
Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of CSS on the
left which states which new elements should be rendered as block-level elements.

**Process & Design who is the site for?**
Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

Target Audience: individuals
* What is the age range of your target audience?
* Will your site appeal to more women or men? What is the mix?
* Which country do your visitors live in?
* Do they live in urban or rural areas?
* What is the average income of visitors?
* What level of education do they have?
* What is their marital or family status?
* What is their occupation?
* How many hours do they work per week?
* How often do they use the web?
* What kind of device do they use to access the web?

Target Audience: Companies
* What is the size of the company or relevant department?
* What is the position of people in the company who visit your site?
* Will visitors be using the site for themselves or for someone else?
* How large is the budget they control?
![Example Site Map](https://blog.hubspot.com/hs-fs/hubfs/dyno-mapper-sitemap-generator.png?width=566&name=dyno-mapper-sitemap-generator.png)

A **wireframe** is a simple sketch of the key information that needs to go on each page of a
site. It shows the hierarchy of the information and how much space it might require.

![wireframe](https://www.freepik.com/blog/app/uploads/2019/05/how-use-wireframes-web-design-Cover-post-100.jpg)

**Visual hierarchy** Most web users do not read entire pages. Rather, they skim to find information. You can use contrast to create a visual hierarchy that gets across your key message and helps users find what they are looking for.
* size
* color
* style

**grouping and Similarity**
When making sense of a design, we tend to organize visual elements into groups. Grouping related pieces of information together can make a design easier to comprehend. Here are some ways this can be achieved.
* Proximity : When several items are placed close together
* Closure : When faced with a complicated arrangement of items
* Continuance : When elements are placed in a line or a curve then they are perceived to be more related
* White Space : Placing related items closer together and leaving a bigger gap between unrelated items.
* color : A background color placed behind related items to emphasize their connection.
* Borders : A line can be drawn around the border of the group or between it and its neighbors.

![Visual hierarchy](https://webdesigntips.blog/wp-content/uploads/2018/11/Hack-Your-Way-To-Great-Design-Basic-Design-Principles-for-WordPress-Developers.png)

**Designing Navigation**Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized. Good navigation tends to follow these principles...
* Concise
* Clear 
* Selective
* Context
* Interactive
* Consistent




