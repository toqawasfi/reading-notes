## key principles of Test-Driven Development (TDD) in Python
1. Writing a unit test and make it fail
2. Writing the feature and make the test pass
3. Refactoring Code

## if __name__ == '__main__'
 Python interpreter reads source file and define few special variables/global variables. 
If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 

## Recursion
programming technique that involves a function calling itself from within its own code.

## Python Modules and Packages
Modules is a python file where the package is a set of modules inside a directory.
 create Module: def mymodule():
 Importing a Module: import my_module

 Creating a Package: to create a package, you need to create a directory with the name of the package, and inside it, create one or more Python files containing your module code. You also need to include an __init__.py file in the package directory to make it a package.
Importing a Package: import my_package.my_module
