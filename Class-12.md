# Read: Class 12

Understanding HTTP status codes, middleware, route parameters, and database schema design is vital for effective web development. These concepts are foundational for creating secure, efficient, and dynamic web applications, ensuring successful communication, customization, and data management in the development process.

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

100's (Informational): Request received, continue or ignore.
200's (Successful): Request successful, server fulfilled it.
300's (Redirection): Client needs to take additional action.
400's (Client Error): Bad client request or access issue.
500's (Server Error): Server failed to fulfill a valid request.

2. What is a status code 202?

HTTP status code 202 means the request has been accepted for processing, but the outcome is not yet complete.

3. What is a status code 308?

HTTP status code 308 means the requested resource has permanently moved to a new location, and the client should update its URL accordingly.

4. What code would you use if an update didn’t return data to a client?

For an update that doesn't return data to the client, use HTTP status code 204 No Content.

5. What code would you use if a resource used to exist but no longer does?

If a resource used to exist but no longer does, use HTTP status code 410 Gone.

6. What is the ‘Forbidden’ status code?

The 'Forbidden' status code is 403, indicating that the client lacks permission to access the requested resource.

[Build A REST API With Node.js, Express, & MongoDB - Quick ](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)- First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Storing MongoDB connection strings in a .env file enhances security by keeping sensitive information separate from code. It allows for easy configuration management, supports different environments, and prevents accidental exposure when sharing or deploying code.

2. What is middleware?

Middleware is software that acts as a bridge between different components in a system. In web development, it handles tasks related to processing incoming requests and outgoing responses. It often includes functions for tasks like authentication, logging, and error handling. Middleware provides a modular way to customize the request-response cycle in web applications.

3. What does `app.use(express.json())` do?

`app.use(express.json())` is Express middleware that parses incoming requests with JSON payloads, making it easy to handle JSON data in your routes by populating req.body with the parsed JSON.

4. What does the `/:id` mean in a route?

In Express.js, `/users/:id` defines a route parameter named id. It captures variable values from the URL, and you can access them in the route handler using req.params.id. This allows for dynamic routing based on the value of id.

5. What is the difference between `PUT` and `PATCH`?


PUT is used to update or create a resource with the complete representation, and it's idempotent. PATCH is used for partial updates, and it may not be idempotent.

6. How do you make a default value in a schema?


To set a default value for a field in a schema, you can use the default property when defining that field. This is often done when creating a schema for a database model, such as with Mongoose for MongoDB or with other similar tools. 

7. What does a 500 error status code mean?

A status code of 500 in HTTP means "Internal Server Error." It indicates that the server encountered an unexpected issue it cannot handle, and it's not the client's fault. The problem resides on the server, requiring investigation and resolution.

8. What is the difference between a status 200 and a status 201?

HTTP status code 200 (OK) signifies a successful request, while status code 201 (Created) indicates the successful creation of a new resource, often used after a POST request.