# Read: Class 07

Understanding object literals and constructor functions in JavaScript is critical in our module. Object literals help organize code and data, while constructor functions with 'this' create reusable, scalable objects. Differentiating 'this' usage is essential for efficient data access and manipulation, aligning with our module's goal of sound programming practices and robust software development

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling.

Domain modeling is an essential step in software development and other knowledge-intensive activities, as it helps to create a structured representation of a specific problem domain. It involves defining and organizing the key concepts, relationships, and rules that govern a particular field of knowledge or a business area.

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. Why should tables not be used for page layouts?

* Semantics: Tables are meant for data, not page structure.
* Accessibility: Tables can hinder accessibility for users with disabilities.
* Maintenance: Tables make page maintenance complex and cumbersome.
* Load Times: Tables can slow down web page loading.
* Responsive Design: Tables don't adapt well to different screen sizes.
* SEO: Tables can harm search engine optimization efforts.
* Separation of Concerns: Mixing content, presentation, and behavior is discouraged.
* Standards Compliance: Table-based layouts do not adhere to modern web standards.
* Web Standards Evolution: Using tables is outdated and doesn't align with current practices.

2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.

Semantic HTML elements are used to provide meaning and structure to the content within a table, making it easier for search engines, assistive technologies, and developers to understand the data.

`<th>` (Table Header Cell):
Description: The `<th>` element is used to define header cells in a table. It represents column or row headers and provides semantic meaning to the content inside. Header cells are typically bold and centered by default.

`<caption>`: The `<caption>` element is used to provide a title or a brief description for the table. It appears at the top of the table and helps users, especially those using screen readers, understand the purpose or context of the table.

`<th>`: The `<th>` (Table Header) element is used within table rows to mark header cells, which typically contain column or row labels. Screen readers can identify `<th>` elements as headers, making it easier for users to navigate and understand the table structure.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. What is a constructor and what are some advantages to using it?

A constructor in programming is a special method or function that is automatically called when an object of a class is created. It is used to initialize the object's state or set up initial values for its properties and attributes. Constructors play a fundamental role in object-oriented programming and are commonly used in many programming languages, including Java, C++, Python, and JavaScript.

* nitialization: Constructors allow you to initialize the object's attributes or properties with default or specific values when the object is created. This ensures that objects are in a valid and usable state from the beginning.

* Encapsulation: Constructors can be used to set up an object's internal state, ensuring that it adheres to the principles of encapsulation. You can make certain attributes private and provide public methods (getters and setters) to access and modify those attributes while controlling access and validation.

* Consistency: By using constructors, you establish a consistent way to create objects of a class, which helps avoid errors and inconsistencies in object creation. It enforces a uniform pattern for initializing objects.

## Things I want to know more about

2. How does the term this differ when used in an object literal versus when used in a constructor?

The usage of the keyword `this` in JavaScript can vary depending on whether it's used in an object literal or in a constructor function.

* Object Literal:
When you use this in an object literal, it refers to the object in which it is defined. It is used to create and access properties and methods within that object.

* onstructor Function:
When you use `this` in a constructor function, it refers to the newly created instance of the object being constructed. Constructors are typically used to create multiple instances of objects with similar structures.

[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)