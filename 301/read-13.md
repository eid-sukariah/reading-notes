# Update/Delete

![#](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data/client-server.png)

At it’s most basic, the web uses a client/server architecture that can be summarized as follows. a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

## how to send the data client side
The `<form>` element defines how the data will be sent. 

The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn’t provided, the data will be sent to the URL of the page containing the form — the current page.

`<form action="https://example.com">`
`<form action="/somewhere_else">`

### GET method