# FileIO & Exceptions

These topics are essential for your module because they teach you how to handle errors gracefully, manage resources efficiently, and follow best practices in Python programming.

[Read & Write Files in Python](https://realpython.com/read-write-files-python/)

[Exceptions in Python](https://realpython.com/python-exceptions/)

1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

The `with` statement in Python is used to open and work with files. It automatically ensures that the file is properly closed when you're done, preventing resource leaks and errors. It simplifies file management and makes your code more concise and robust.

2. Explain the difference between the `‘read()’` and `‘readline()’` methods for file objects in Python. Provide examples of when to use each method.

`read()` reads the entire file or a specified number of bytes as a single string. `readline()` reads one line at a time from the file and returns it as a string. Use `read()` for whole-file reading and `readline()` for line-by-line processing.

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

Exception handling in Python uses `try`, `except`, and optionally `finally` blocks:

* try contains code that might raise an exception.

* except handles specific exceptions or a generic one.

* finally (optional) ensures code inside it is always executed.

Chatgpt example:

try:
    # Code that may raise an exception

    num1 = int(input("Enter a number: "))
    num2 = int(input("Enter another number: "))
    result = num1 / num2

except ZeroDivisionError:
    print("You can't divide by zero.")

except ValueError:
    print("Invalid input. Please enter valid numbers.")

else:
    print(f"The result is: {result}")

finally:
    print("Execution completed.")