https://github.com/toqawasfi/reading-notes/blob/main/Class07.md
Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
Local Scope: A variable declared within a function or a code block has local scope. 
Global Scope: A variable declared outside of any function or code block has global scope

local Ex:
 def greet():
    name = "John"  # local variable
    print("Hello, " + name)

greet()

global EX :
count = 0  # global variable

def increment():
    global count  # declare count as a global variable inside the function
    count += 1

increment()
print(count)  # Output: 1

How do the global and nonlocal keywords work in Python, and in what situations might you use them?
n Python, the global and nonlocal keywords are used to specify the scope of a variable and how it should be accessed and modified within nested functions or code blocks.

In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
to detrmine how much this algorithem could take time.

Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials. 
its just about creating method recives parameter represnts dices number ,then a random numbers would be generated and the o/p will assigned in tuple.

