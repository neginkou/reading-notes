# Read: Class 05

Understanding map and reduce is crucial in my studies because they are fundamental to functional programming, essential for efficient array transformations and reductions. Mastery of these functions contributes to code clarity, aligns with modern development practices, and forms a crucial part of your toolkit in web development and JavaScript programming.

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. What is the `single responsibility principle` and how does it apply to components?

The Single Responsibility Principle (SRP) in React components means that each component should have only one job or responsibility. This helps keep code modular, maintainable, and reusable.

2. What does it mean to build a `static` version of your application?

Building a "static" version of your application means creating a simplified representation without dynamic features or user interactions. It focuses on the initial visual design and layout before incorporating interactive elements or fetching dynamic data.

3. Once you have a static application, what do you need to add?

1. Dynamic data fetching.
2. User interaction handling.
3. State management.
4. Routing (if needed).
5. Validation and error handling.
6. Performance optimizations.
7. Security measures.
8. Testing for bugs.
9. Accessibility considerations.
10. Deployment preparations.

4. What are the three questions you can ask to determine if something is state?

* Does it change over time?
* Can it be derived from props or other state?
* Does it affect the component's rendering?

5. How can you identify where state needs to live?

1. Define the minimal state required for a component.
2. Determine which component owns or controls the state.
3. Lift state up if it's shared among components.
4. Consider where state changes will be triggered.
5. If state affects UI rendering, keep it in the component's state.
6. Start from top-level components and work down.
7. Avoid redundant state; lift it to a common ancestor.
8. Use `useState` in functional components and `state` in class components.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?

A `higher-order function`` is a function that either:

1. Takes one or more functions as arguments (parameters).
2. Returns a function as its result.
In other words, a higher-order function treats functions as first-class citizens, allowing them to be used as values, passed as arguments, and returned as results.

2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

`greaterThan` is a higher-order function that takes a parameter `n` and returns a new function.

3. Explain how either map or reduce operates, with regards to higher-order functions.

`map` transforms each array element using a provided function, creating a new array with the results. `reduce` accumulates array elements into a single value by applying a callback function iteratively. Both are higher-order functions, taking functions as arguments to define their behavior.