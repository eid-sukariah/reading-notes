# The past, present & future of local storage for web applications
Persistent local storage is one of the areas where native client applications have held an advantage over web applications.
Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
1. Cookies are included with every HTTP request, thereby slowing down your web application 
2. sending data unencrypted over the internet 
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## LOCAL STORAGE HACKS BEFORE HTML5
In the beginning, there was only Internet Explorer. Or at least.
- userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
- In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.”
- In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. Gears can store unlimited amounts of data per domain in SQL database tables.
## HTML5 Storage
 Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. 
 HTML5 Storage is based on named key/value pairs.
