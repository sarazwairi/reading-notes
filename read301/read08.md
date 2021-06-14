# RESTful web API design

## API Design Best Practices

1. What does REST stand for?

Representational State Transfer.

2. REST APIs are designed around a resources.

3. What is an identifer of a resource? Give an example.

URI that uniquely identifies that resource. For example, the URI for a particular customer order :https://adventure-works.com/orders/1.


4. What are the most common HTTP verbs?

GET, POST, PUT, PATCH, and DELETE.

5. What should the URIs be based on?

based on nouns (the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.

https://adventure-works.com/orders

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

APIs that expose a large number of small resources. and it's a bad thing because it's impose a load on the web server.

8. What status code does a successful GET request return?

returns HTTP status code 200 (OK).

9. What status code does an unsuccessful GET request return?

404 not found

10. What status code does a successful POST request return?

HTTP 201 created

11. What status code does a successful DELETE request return?

the web server should respond with HTTP status code 204, indicating that the process has been successfully handled.
