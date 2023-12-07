# Read: Class 08

In the context of our module, a solid grasp of HTTP status codes is paramount for effective web development. These codes serve as the language of communication between clients and servers, aiding in debugging, guiding client-side decisions for optimal user experiences, influencing RESTful API design, and contributing to secure authentication practices.

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?

REST stands for Representational State Transfer. It's an architectural style for designing networked applications, commonly used in web services and APIs. It relies on standard HTTP methods for CRUD operations on resources and emphasizes stateless communication.

2. REST APIs are designed around a _stateless communication model___.

3. What is an identifier of a resource? Give an example.

An identifier of a resource in the context of REST typically refers to a Uniform Resource Identifier (URI) or a URL (Uniform Resource Locator) that uniquely identifies that resource.

Example:
For a hypothetical resource representing a book, the URI or URL could be:

https://example.com/books/123

Here, "123" is the identifier for the specific book resource.

4. What are the most common HTTP verbs?

* GET: Retrieve data from a specified resource.
* POST: Submit data to be processed to a specified resource.
* PUT: Update a specified resource with new data.
* DELETE: Delete a specified resource.
* PATCH: Apply partial modifications to a resource.
* HEAD: Retrieve the headers of a specified resource.
* OPTIONS: Get information about the communication options for a specified resource.
* TRACE: Perform a message loop-back test along the path to the target resource.
* These HTTP verbs are used in the context of RESTful APIs to perform various actions on resources.

5. What should the URIs be based on?

URIs should be based on the resource they identify, using meaningful nouns `(e.g., /users, /products)`. Use plural nouns, hyphens or underscores for word separation, and represent hierarchy when applicable. Keep URIs concise and avoid incorporating verbs.

6. Give an example of a good URI.

https://api.example.com/users/123

`https://api.example.com` is the base URL.
`/users` represents the collection of user resources.
`/123` is the unique identifier for the specific user resource.

7. What does it mean to have a `‘chatty’` web API? Is this a good or a bad thing?

A "chatty" web API requires numerous small requests for specific data, leading to performance overhead, increased latency, network inefficiency, and complexity for clients. It is generally considered a disadvantage, and efficient batch operations are recommended to address these issues.

8. What status code does a successful `GET` request return?

A successful GET request typically returns a status code of 200 OK. This status code indicates that the request was successful, and the server has successfully fulfilled the client's request, returning the requested data.

9. What status code does an unsuccessful `GET` request return?

An unsuccessful GET request can return various status codes, including:

404 Not Found
400 Bad Request
401 Unauthorized
403 Forbidden
500 Internal Server Error

10. What status code does a successful `POST` request return?

A successful POST request typically returns a status code of 201 Created. This status code indicates that the request has been fulfilled, resulting in the creation of a new resource on the server. In addition to 201, a server might also respond with a 200 OK status in the context of a successful POST request, but 201 Created is more specific to the creation scenario.

11. What status code does a successful `DELETE` request return?

A successful DELETE request typically returns a status code of 204 No Content. This status code indicates that the server has successfully processed the request and that there is no additional content to send in the response body. The use of 204 No Content for a successful DELETE request signifies that the resource has been deleted, and there is no need to return a representation of the deleted resource in the response.
