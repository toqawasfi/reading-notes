# What are the key differences between classes and objects in Python?
class is the blueprint which defines the structure of the output while the object is an instance ,where this convept is common between all languages.
Classes define attributes and methods, which can be accessed and modified by objects. Instances of a class can have their own set of attributes and can call their own set of methods. Classes can inherit from other classes, and they can also have class-level attributes and methods.

# Explain the concept of recursion.
Recursion is a programming technique rely on dividing a problem into subproblems until reaching basecase.

Ex: Factorial
def factorial_recursive(n):
    # Base case: 1! = 1
    if n == 1:
        return 1

    # Recursive case: n! = n * (n-1)!
    else:
        return n * factorial_recursive(n-1)

for best practicing :
- Base Case
- Repeated problem
- Stable Formula

# What is the purpose of pytest fixtures and code coverage in testing Python code? 

pytest fixtures: to add mor setting for our environment 
"code coverage", checking that your tests have run all of the code.
so using both pytest fixtures and code coverage you will hve seted and tested program.