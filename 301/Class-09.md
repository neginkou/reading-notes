# Read: Class 09

Understanding modules and importing is crucial in this module for organizing code, promoting modularity, and integrating external functionalities efficiently. These concepts are fundamental for building maintainable and scalable codebases, aligning with industry best practices in software development.

 [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

1. What is functional programming?

Functional programming is a programming paradigm that emphasizes the use of functions as first-class citizens, immutability (data does not change), and avoids side effects. Key principles include pure functions, higher-order functions, and recursion. It's known for conciseness, clarity, and the ability to handle complex problems through composable functions. Examples of functional programming languages include Haskell, Lisp, and Scala.

2. What is a pure function and how do we know if something is a pure function?

A pure function is a function that consistently produces the same output for the same input and has no side effects. It doesn't modify external state, making it predictable and easier to understand. Pure functions are identified by their deterministic behavior and lack of observable side effects.

3. What are the benefits of a pure function?

1. Predictability: Always produce the same output for the same input.
2. Testability: Easy to test in isolation for reliable unit testing.
3. Parallelism: Inherently thread-safe, simplifying concurrent programming.
4. Cacheability: Results can be cached for the same inputs.
5. Debugging: Facilitates debugging with no hidden dependencies or side effects.
6. Referential Transparency: Allows easy substitution, aiding optimization.
7. Composability: Naturally composable for modularity and code reuse.
8. Functional Programming: Aligns with functional programming principles for robust code.

4. What is immutability?


Immutability in programming means once an object is created, its state cannot be changed. Instead of modifying existing objects, operations create new objects with updated values. This promotes predictability, simplifies debugging, ensures thread safety, and aligns with functional programming principles. Examples include strings and tuples.

5. What is Referential transparency?

Referential transparency means a function, given the same inputs, always produces the same output and has no observable side effects. This property simplifies reasoning, facilitates optimization, and makes testing easier. It is closely related to pure functions.

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

1. What is a module?

A module is a self-contained unit in a program that groups related functions, procedures, or data structures. It promotes code organization, isolation, and reuse by encapsulating functionality, providing a namespace, and allowing components to be independent and easily maintainable.

2. What does the word `‘require’` do?

In JavaScript `(Node.js)`, require is used to import external modules or files, allowing the use of their functionality in the current script. It's a way to include and use code from other files or libraries.

3. How do we bring another module into the file the we are working in?


In JavaScript (Node.js), you can bring another module into the file you are working on using the require statement or, in more recent versions of JavaScript (ES6 and later), the import statement. 

4. What do we have to do to make a module available?

To make a module available in a JavaScript file, you need to use either the require statement (for CommonJS modules) or the import statement (for ES6 modules).