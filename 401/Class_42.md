# Pythonisms

[Dunder Methods](https://dbader.org/blog/python-dunder-methods)

[Iterators](https://dbader.org/blog/python-iterators)

[Generators](https://dbader.org/blog/python-generators)

[What are Generators](https://realpython.com/lessons/what-are-python-generators/)

[Decorators](https://realpython.com/primer-on-python-decorators/)

1. What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.

Dunder methods, short for "double underscore" methods (also called magic methods or special methods), are special methods in Python that allow you to customize the behavior of classes and objects. These methods are surrounded by double underscores on both sides of their name.

One common dunder method is __init__, which is used for initializing objects created from a class. It allows you to define how an object should be initialized when it is created. Here's an example:

`class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def __str__(self):
        return f"({self.x}, {self.y})"

`point = Point(3, 4)
print(point)  # Output: (3, 4)`

In this example, __init__ is used to initialize a Point object with x and y coordinates. The __str__ method is another dunder method that defines how the object should be represented as a string when using print. This allows you to customize the behavior of the print function for instances of the Point class.

2. Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?

An iterator in Python is an object that implements the iterator protocol, consisting of __iter__() and __next__() methods. These methods allow the object to return elements one at a time. You can create a custom iterator by defining a class with these methods. Custom iterators are important for enabling iteration over objects in a custom way, such as iterating over elements in a specific order or from a non-traditional sequence.

3. What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.

A generator in Python is a special type of iterator that is created using a function with the yield keyword. While a regular function computes all its values at once and returns them, a generator function computes one value at a time, suspending its state between each value and resuming execution from where it left off when the next value is requested. This makes generators memory-efficient for large datasets or infinite sequences.

Here's an example of a generator function that generates a sequence of Fibonacci numbers:

`def fibonacci_generator(n):
    a, b = 0, 1
    count = 0
    while count < n:
        yield a
        a, b = b, a + b
        count += 1

#Create a generator object
fibonacci = fibonacci_generator(5)

#Iterate over the generator to get Fibonacci numbers
for num in fibonacci:
    print(num)`

In this example, fibonacci_generator is a generator function that yields Fibonacci numbers up to a specified limit n. When the generator object fibonacci is created, it doesn't compute all the Fibonacci numbers at once. Instead, it computes and yields one number at a time, only when requested in the for loop.

4. Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.

Decorators in Python are functions that modify the behavior of other functions or methods. They are applied using the @ symbol followed by the decorator's name above the function definition. Decorators are commonly used for tasks like logging, authentication, and memoization. Here's a simple example of a decorator that logs function calls:

def log_function(func):
    def wrapper(*args, **kwargs):
        print(f"Calling function: {func.__name__}")
        result = func(*args, **kwargs)
        print(f"Finished calling function: {func.__name__}")
        return result
    return wrapper

@log_function
def add(a, b):
    return a + b

result = add(1, 2)
print(result)

In this example, the log_function decorator adds logging to the add function, printing messages before and after the function is called.