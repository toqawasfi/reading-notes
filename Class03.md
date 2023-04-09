## why this topic matters??
As a developers for sure we will import and export files so learning how to open , close ,read and write over file is very important.

## What is the purpose of the ‘with’ ?

its a closing method indecates the end of a file ,so instead of using try finally method .it allows for cleaner code and makes handling any unexpected errors easier.

## Explain the difference between the ‘read()’ and ‘readline().
read: this method reads from file the number of bytes size.

readline: The readline method takes one parameter i.e size, the default value for the size parameter is -1. It means that the method will return the whole line. It is an optional parameter, we can specify the number of bytes from a line to return.

EX: lets suppose we have have  personal profile as atext file contains the following :
Toqa Bany Yassen ,Full Stack Develpoer
Toqa was born in Irbid in 13 oct.

file = open(" personal.txt", "r")
example1 = file.readline()
example2 = file.readline(8)
print(example1)
print(example2)

output :Toqa Bany Yassen ,Full Stack Develpoer
       :Toqa was

       Ex2:

 f = open("personal.txt", "r")
 print(f.read())

 output: Toqa Bany Yassen ,Full Stack Develpoer
Toqa was born in Irbid in 13 oct.


# Briefly describe the concept of exception handling in Python.
when syntactically correct code runs into an error, Python will throw an exception error. This exception error will crash the program if it is unhandled. so here the concept of exception handling appears to handle such errors

When an exception occurs in a program running this function, the program will continue as well as inform you about the fact that the function call was not successful.
## try and except:
What you did not get to see was the type of error that was thrown as a result of the function call. In order to see exactly what went wrong, so for this we need try ,except.

## finally :
everything in the finally clause will be executed. It does not matter if you encounter an exception somewhere in the try or else clauses. 

Ex:
try:
    linux_interaction()
except AssertionError as error:
    print(error)
else:
    try:
        with open('file.log') as file:
            read_data = file.read()
    except FileNotFoundError as fnf_error:
        print(fnf_error)
finally:
    print('Cleaning up, irrespective of any exceptions.')