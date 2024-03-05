# Ten Thousand 2

These topics matter in programming because they improve code quality, prevent issues, and optimize software for efficiency and scalability.

[Python Scope](https://realpython.com/python-scope-legb-rule/)

[Big O notation is simpler than you might think](https://www.youtube.com/watch?v=dNorFNlDbX0)

[Rolling Dice Examples](https://web.archive.org/web/20220608035657/https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Random)

1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.

* Local Scope: 
Variables defined inside a function are local and can only be used within that function.
* Global Scope:
Variables defined outside functions can be accessed and modified anywhere in the program.

Example of local scope:
def my_function():
    x = 10  # Local variable
    print(x)

my_function()

Example of global scope:
y = 20  # Global variable

def my_function():
    print(y)  # Accessing the global variable y

my_function()

Local variables are temporary and limited to the function, while global variables are accessible everywhere.

2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?

* Global Keyword: Used to declare and modify global variables from within functions.

* Nonlocal Keyword: Used to access and modify variables from enclosing (outer) functions' scopes within nested functions.

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.

Big O notation is a way to measure and compare how the performance of algorithms scales with input size. It helps us choose efficient algorithms, identify bottlenecks, and communicate about efficiency in a standardized way.

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.

To simulate a dice roll in Python and calculate the probability of rolling a specific number (e.g., 6) over many trials:

import random

def roll_dice():
    return random.randint(1, 6)

num_trials = 100000
target_number = 6
count = sum(1 for _ in range(num_trials) if roll_dice() == target_number)
probability = count / num_trials

print(f"Probability of rolling a {target_number}: {probability:.4f}")