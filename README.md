# Python_Crash_Course_Coursera

## What it is programming?

Syntax: Is the rules for how a sentence is contructed

Semantics: It's the actual meaning of statments

Script: A program that's short, simple, and can be written very quickly.

## What it is Automation?

Automation: Is the process of replacing manual steps with one that happens automatically

Is importan to understand that Artificial Intelligence is not the same that automation, AI involves training a computing machine to perform more complex task through a process called machine learning.

## Introduction to Python

Python interpreter: The program that reads what's in the recipe and translate in into instructions for your computer to follow.

Functions: Pieces of code that performs a unit of work.
 
Keywords: A reserve words that are used to construct instructions.

List of Keywords:
- Values: True, False, None
- Conditions: if, elif, else
- Logical operators: and, or, not
- Loops: for, in, while, break, continue
- Functions: def, return

Arithmetic operators: 

- x + y            Addition + operator returns the sum of x plus y
- x - y             Subtraction - operator returns the difference of x minus y
- x * y            Multiplication * operator returns the product of x times y
- x / y             Division / operator returns the quotient of x divided by y
- x**e            Exponent ** operator returns the result of raising x to the power of e 
- x**2            Square expression returns x squared
- x**3            Cube expression returns x cubed
- x**(1/2)    Square root (½) or (0.5) fractional exponent operator returns the square root of x
- x // y           Floor division operator returns the integer part of the integer division of x by y
- x % y          Modulo operator returns the remainder part of the integer division of x by y

## Expressions and variables

- Variables: Represent data stored as strings, tuples, dictionaries, lists, and objects (note: future readings explain these categories)
- Keywords: Special words that are reserved for specific purposes and that can only be used for those purposes
- Operators: Symbols that perform operations on objects and values
- Expressions: A combination of numbers, symbols, and variables to compute and return a result upon evaluation
- Functions: A group of related statements to perform a task and return a value
- Conditional statements: Sections of code that direct program execution based on specified conditions

### Naming rules and conventionsNames cannot contain spaces.

- Names may be a mixture of upper and lower case characters.

- Names can’t start with a number but may contain numbers after the first character.

- Variable names and function names should be written in snake_case, which means that all letters are lowercase and words are separated using an underscore. 

- Descriptive names are better than cryptic abbreviations because they help other programmers (and you) read and interpret your code. For example, student_name is better than sn. It may feel excessive when you write it, but when you return to your code you’ll find it much easier to understand.

### Data Type

- String
- Integer
- Double

Implicit convertion: The interpreter automatically converts one data type into another.

### Functions

To define a function you need to use the word `def` later you put the name of the function and later () and if you need a parameter.
`def greeting(name)
print ("Hi", name)`.

To execute a function you need to call it 
`greeting(Hugo) -> Hi Hugo`

Built-in functions
- print()
- type()
- str()
- sorted() = sorts the components of a list, works on any iterable, like a string and return the sorted elements in a list. Also does not change the iterable that it sorts.
- Max() returns the largest numeric input passed into it.
- Min() Returns the smallest numeric input passed into it

Return Values

If you wan to return a value and later use it in your code, here is where you can use `return`
 