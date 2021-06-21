# CRUD

## Status Codes Based On REST Methods

### In your own words, describe what each group of status code represents:

100’s =Informational status codes.

200’s = Success codes

300’s = Redirection codes.

400’s = Client error codes.

500’s = Server error codes.

* What is a status code 202?

An async request met the valudation requirements, but it wasn't necessarily fully processed

* What is a status code 308?

 There is an error with the accessing the Microsoft SQL Server.

* What code would you use if an update didn’t return data to a client?

A 204, 'No Content' error. For things like saving something they have just changed.

* What code would you use if a resource used to exist but no longer does?

A 410 'Gone' error. It is similar to the 404, which is 'Not Found,' but it specifies that the system knows it was once in existence.

* What is the ‘Forbidden’ status code?

403 'Forbidden.' This happens after authorization has been accepted, or if auth is not necessary, but the client does not have correct permissions to use the resource.


## Build a REST API Link

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?

This is because when working on the code locally, you want to store the database as a local environment variable. This adds security and flexibility.

* What does app.use(express.json()) do?

This sets up the server to accept JSON. It also lets the server use middleware. Middleware = Code that runs when the server gets request, but before it is passed to routes.

* What does the /:id mean in a route?

It means that whatever is passed in after the first slash is an id, which lives in the request params, and can be accessed as request.params.id.

* What is the difference beween PUT and PATCH?

Patch is only updating what the user passes- put would update all the information at once. Patch only updates what is given.

* How do you make a defalut value in a schema?

Within the curly brackets enclosing the information for a specific key/value pair in a schema, place a default key that will contain a value that it will default to if no information is given in place of it.

* What does a 500 error status code mean?

A 500 error means that there has been an error on the server. This is good to be placed within the catch of a try/catch statement, because if it fails, something is wrong within that function.

* Status 200 vs status 201

201 = successfully created object 200 = everything was successful The 201 is more specific, so if it can be used, for example in a post route, it should be used. More information is always better!

refrences:

https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/

https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw