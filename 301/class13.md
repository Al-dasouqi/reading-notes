# Which HTTP Status Code To Use For Every CRUD App
The HTTP specification defines many status codes we can use when responding to our clients.

These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

200 OK - It's the basic status code to tell the client everything went good.

303 See Other - Like the 202 code but using a Location header field in response to informing the client about the location of the created resource or an endpoint that lets the client check for the status of the creation process.

This status code will let the client come back to the current URL for every request.

As we see the 404 is a client error status code, but it could very well be that we did something wrong on the backend.

Often clients can't access every resource on the backend, so we need a way to tell them about it.
