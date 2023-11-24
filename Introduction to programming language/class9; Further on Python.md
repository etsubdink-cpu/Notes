# Further on Python
##### Todays contents:-
- Functions, recursion
- lambda → Map/filter
- OOP & POP
- Class & objects
- user-built Module

###### Functions
A function is a block of code that performs a specific task. Dividing a complex problem into smaller chunks makes our program easy to understand and reuse.
###### Types of function
 There are two types of function in Python programming:
 1. *Standard library functions **- These are built-in
    functions in Python that are available to use.
    Almost all keywords are functions
    print(),len(),input()….
 2. *User-defined functions **- We can create our own
    functions based on our requirements.

##### Creating Functions

syntax -> def **function_name**(argument)
*example:-*
def greet(name):
    print(f"Hello, {name}!") 
greet("Alice")

##### Function Arguments

They are used to take value while calling and insert it inside the function.
#syntax
def add_numbers(a, b):
    sum = a + b
    print(f" The sum of {a} and {b} is {sum}")

 Call the function
add_numbers(3, 4)
*example:-*
def greet(name, greeting="Hello"):
    print(f"{greeting}, {name}!")
Call the function
greet("Alice")
greet("Bob", "Hi")
#### Return statement

->A Python function may or may not return a value.
If we want our function to return some value to a function call, we use the ‘return’ statement.