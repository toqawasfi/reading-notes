Link:https://github.com/toqawasfi/reading-notes/blob/main/Class08.md

## Question one :
- The basic syntax of list comprehnsion is :
new_list = [expression for item in iterable if condition]

-  how does it differ from using a for loop to create a list?
Here just you need to implement one line code to create a list with the element's values you need ,just add the expresion you want.

- EX of squre :
squares = [x**2 for x in range(10)]

print(squares)

## Question two :
What is a decorator in Python?
decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.


## Question three :
concept: a way to add functionality to a function without modifying the function itself. Decorators are written using the @decorator_name syntax and are placed above the function that they are modifying.Decorators are written using the @decorator_name syntax and are placed above the function that they are modifying.

- common cases :
Logging: Decorators can be used to log the inputs, outputs, and execution time of a function, which can be useful for debugging and performance tuning.

Caching: Decorators can be used to cache the results of a function, which can improve performance by avoiding unnecessary computations.

Authorization and authentication: Decorators can be used to check whether a user is authorized to access a particular function or resource, or to authenticate the user before allowing access.
- EX:
def register(func):
    """Register a function as a plug-in"""
    PLUGINS[func.__name__] = func
    return func

@register
def say_hello(name):
    return f"Hello {name}"
