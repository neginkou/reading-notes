# Read: Class 06

Understanding the problem domain, objects, and the Document Object Model (DOM) is essential to the module I'm studying because they form the foundational building blocks of web development. Incorporating these concepts into my study module will empower me with the knowledge and skills necessary to develop effective, user-focused web applications. Whether I'm learning front-end or full-stack development, a solid grasp of the problem domain, objects, and the DOM is fundamental to my success in the field.


[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend you grew up with?

It's a small rectangular device called a smartphone that's like a pocket-sized computer. People use it for making calls, sending messages, taking photos, and browsing the internet.

2. What are some advantages to creating object literals?

* Object literals provide a clear and simple way to structure data.
* They enhance code readability and organization.
* Easy access and manipulation of properties.
* Group related data and methods together.

3. How do objects differ from arrays?

 Objects:

* Key-value pairs, used for modeling entities.
* Accessed by keys with dot or bracket notation.
* Ideal for structured data with named attributes.
* Property order is not guaranteed.

 Arrays: 

* Ordered, indexed collections of values.
* Accessed by index.
* Best for lists of similar items or ordered data.
* Element order is guaranteed, with various manipulation methods.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

Bracket notation is used when you need to access an object's property with a key that contains special characters, spaces, or is stored as a variable. 
For example: the object person has properties with keys containing spaces ("first name" and "last name"). When trying to access the property with a space using dot notation, it would result in a syntax error. However, using bracket notation allows you to access these properties without any issues.

5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

`this` refers to the current object, which is `dog` in this case. It allows you to access the object's properties and methods from within the object itself.
The advantage of using `this` in this code is that it allows you to access and use the object's own properties and methods within its own functions. This is particularly useful when you have multiple instances of similar objects, as it ensures that the correct object's properties and methods are used, making the code more reusable and maintainable.

[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. What is the DOM?

The DOM, which stands for Document Object Model, is a programming interface for web documents. It represents the page so that programs can change the document structure, content, and style. Essentially, the DOM is a way to interact with and manipulate web pages using programming languages like JavaScript.

2. Briefly describe the relationship between the DOM and JavaScript.

JavaScript and the DOM work together to make web pages interactive and dynamic. JavaScript provides the scripting capabilities, and the DOM offers a structured way to access and manipulate the content and structure of web documents. This synergy is fundamental to modern web development.

## Things I want to know more about