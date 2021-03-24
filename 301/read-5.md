# HEROKU

Heroku is a polyglot[speaking, many languages.] platform it lets you:
![#](https://mycervello.com/wp-content/uploads/2015/09/Heroku-Child-Page_SP-diagram.png)

1. build
2. run
3. scale applications in a similar manner across all the languages
utilizing the dependencies and Procfile. The Procfile exposes an architectural aspect of your application

**Deploying applications**:
Heroku platform uses Git as the primary means for deploying applications
When you create an application on Heroku, it associates a new Git remote, typically named heroku, with the local Git repository for your application. $ git push heroku master.

First of all, we need to create a JavaScript file. Let’s name it server.js:

`http.createServer( function( request, response) {`

`response.writeHead( 200, {"Content-Type": "text/plain"} );`

`response.write( "It's alive!" );`

`response.end();`

`}).listen(3000);` 