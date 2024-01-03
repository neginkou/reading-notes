# Read: Class 10

Mastering debugging and using a debugger is crucial in my current module. These skills are fundamental for identifying and resolving issues in software development, ensuring robust and reliable code. Proficiency in debugging enhances my problem-solving abilities and contributes to a disciplined approach in the software development lifecycle.

[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

1. What is a `‘call’`?

In the context of programming and software development, a "call" typically refers to the act of invoking or executing a function or method. When you "call" a function or method, you are instructing the program to execute the code within that function or method.

2. How many `‘calls’` can happen at once?

The number of simultaneous calls in a system depends on its architecture, concurrency model, and available resources. Modern systems can achieve concurrency through asynchronous programming, threads, and processes, and can handle multiple calls simultaneously. 

3. What does `LIFO` mean?

LIFO stands for "Last In, First Out." It means that the last item added to a collection is the first one to be removed or processed. This concept is commonly used in data structures like stacks.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

main
   ↓
firstFunction
   ↓
secondFunction
   ↓
thirdFunction

5. What causes a Stack Overflow?

A stack overflow occurs when the call stack is full due to either infinite recursion, deep recursion, or insufficient stack size. Infinite recursion happens when a function calls itself indefinitely, while deep recursion occurs with an excessive chain of nested function calls.

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7chttps://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

1. What is a `‘reference error’`?

Variable or function that is not defined or has not been declared in the current scope. This error indicates that the interpreter or compiler cannot find the referenced entity, leading to a runtime error.

2. What is a `‘syntax error’`?

A "SyntaxError" is a type of error that occurs in programming when the structure or syntax of a code violates the rules of the programming language. Syntax errors prevent the interpreter or compiler from parsing and understanding the code.

3. What is a `‘range error’`?

A "RangeError" is a type of error in programming that occurs when a value is not within the expected range or set of allowable values. This error is typically thrown by the JavaScript runtime environment when an operation tries to create, manipulate, or access a value that is outside the permissible range.

4. What is a `‘type error’`?

A "TypeError" is a type of error in programming that occurs when an operation is performed on an object of an inappropriate type. This error typically happens when there is an attempt to use a value or invoke a method on a data type that doesn't support the specific operation.

5. What is a breakpoint?

A breakpoint is a designated point in the source code of a program where the execution should temporarily pause to allow developers to inspect the state of the program, variables, and memory. Breakpoints are a fundamental debugging tool used by developers to understand and troubleshoot the behavior of their code.

6. What does the word `‘debugger’` do in your code?

A debugger is a tool that developers use to find and fix issues (bugs) in their code. It provides features that allow developers to control the execution of their program, inspect the state of variables, and track the flow of code during runtime. 


[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
