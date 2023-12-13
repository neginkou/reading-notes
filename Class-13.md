
# Read: Class 13

Creating RESTful APIs is vital for our module, aligning with core web development principles. It offers a structured approach to building efficient and standardized web services, crucial for scalable data interaction and adhering to industry best practices. Mastering these concepts ensures not just functional but also well-documented and maintainable APIs, making it essential for our studies.

[CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

1. Which HTTP method would you use to update a record through an API?

* Use PUT if sending the entire updated resource.

* Use PATCH for partial updates.

2. Which REST methods require an ID parameter?

* GET: Retrieve a resource.

* DELETE: Delete a resource.

[Speed Coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo)

1. What’s the relationship between REST and CRUD?

REST: Architectural style for designing networked applications.
CRUD: Basic operations - Create, Read, Update, Delete.

Relationship:

RESTful APIs often implement CRUD using standard HTTP methods.
Create (POST), Read (GET), Update (PUT/PATCH), Delete (DELETE).

2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?


Define Resources:
Identify entities/resources.
Determine attributes and relationships.

Choose Endpoints:
Design URIs for resources.
Establish naming conventions.

Select HTTP Methods:
Assign CRUD operations to methods.
Define actions for each resource.

Create Data Models:
Design resource representations.
Set up a corresponding database schema.

Implement Logic and Documentation:
Develop server-side logic for CRUD.
Document API details, including endpoints and methods.
