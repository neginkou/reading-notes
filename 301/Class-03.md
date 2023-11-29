# Read: Class 03

Mastering the ability to pass methods from parent to child components in React is vital. It enables reusable components, facilitates communication between components, maintains a clear hierarchy, and enhances modularity and testability in your application.


[React Docs - lists and keys](https://react.dev/learn#rendering-lists)

1. What does .map() return?

 The `.map()` method in JavaScript returns a new array created by applying a specified function to each element of the original array.

 2. If I want to loop through an array and display each value in JSX, how do I do that in React?

 In React, you can use the `.map()` method to loop through an array and render JSX for each element.

 3. Each list item needs a unique __key attribute.__.

 4. What is the purpose of a key?

 The `key` attribute in React is used to give each element in a list a unique identifier. It helps React efficiently update, add, or remove elements by providing a stable identity for each item in the virtual DOM. This is crucial for optimizing performance during dynamic rendering and state changes.

 [The Spread Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

 1. What is the spread operator?

 The spread operator `(...)` is a syntax in JavaScript that allows you to expand elements of an iterable (like an array or string) or properties of an object. It provides a concise way to copy arrays, merge objects, and more.

 2. List 4 things that the spread operator can do.
  
  1. Copying Arrays
  2. Concatenating Arrays
  3. Copying Objects
  4. Merging Objects

  3. Give an example of using the spread operator to combine two arrays.

  ChatGPT =>

  const array1 = [1, 2, 3];
const array2 = [4, 5];

// Combining arrays using the spread operator
const combinedArray = [...array1, ...array2];

console.log(combinedArray);
// Output: [1, 2, 3, 4, 5]

4. Give an example of using the spread operator to add a new item to an array.

const originalArray = [1, 2, 3];
const newItem = 4;

// Adding a new item to the array using the spread operator
const newArray = [...originalArray, newItem];

console.log(newArray);
// Output: [1, 2, 3, 4]

5. Give an example of using the spread operator to combine two objects into one.

const object1 = { a: 1, b: 2 };
const object2 = { b: 3, c: 4 };

// Combining objects using the spread operator
const combinedObject = { ...object1, ...object2 };

console.log(combinedObject);
// Output: { a: 1, b: 3, c: 4 }

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=n-6i_WGIOKE)

1. In the video, what is the first step that the developer does to pass functions between components?

The first step he uses to pass functions between components is to define the function in the parent component (the component that owns the state or logic you want to modify) and then pass it down to the child component as a prop.

2. In your own words, what does the handleClick function do?

The `handleClick` function is responsible for updating the count in the parent component. 

3. How can you pass a method from a parent component into a child component?

Define the method in the parent component:
Create a function within the parent component containing the desired logic.
Pass the method as a prop:
Include the child component in the parent's render, passing the method as a prop.
ccess and use the method in the child component:
Receive the method as a prop in the child component, then call it as needed.

4. How does the child component invoke a method that was passed to it from a parent component?

In React, a child component can invoke a method that was passed to it from a parent component by calling the method through the props. 