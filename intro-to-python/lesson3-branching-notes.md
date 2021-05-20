# Branching
Ada Build - Intro to Python: Lesson 3

## Relational Operators

Relational operators allow us to compare 2 or more values. 
* In Python, we can use relational operators on all numbers and strings. We can use equals and does not equal on lists and dictionaries. 
* Equals sign = is the assignment operator. This is very very different than double equals sign == which is the EQUALITY operator. 
* The result of a relational operator (True or False) is known as a boolean. 
* Relational operators can be chained together like: 0 < x <= 100 or 10 > x > 1 

### Boolean values
* The two posisble values of the boolean data type (bool) are True and False.
* A non-boolean value that evaluates to False is called "falsey" or "falsy".

A list of all "falsy" values in Python:
    * Sequences and Collections
        * Empty lists, tuples, dictionaries, sets, strings, and ranges (range(0))
    * Numbers
        * Zero of any numeric type
        * Integer 0
        * Float 0.0
        * Complex 0j
    * Constants
        * None
        * False

A complex number contains two parts: real and imaginary. The imaginary part is written with the "j" suffix. The complex() function can also be used to create a complex number. 

* A non-boolean value that evaluates to True is called "truthy"
    * Everything not included in the "falsy" list above is "truthy" in Python
## Conditionals
Conditional statements allow our programs to take different paths based on different inputs. To create conditional statements, we use the if, elif, and else keywords. 

Indentation is very important for conditional statements. They must be properly indented in order to execute. 

Each indented section of code is called a block. Each block describes the behavior the code performs for each different condition. 

## Logic Errors & Syntax Errors
Logic errors are a bug that cause our program to behave incorrectly. They may result in unintended or undesired output. 

Logic errors are different from syntax errors because the program still runs but performs contrary to expectations. 

In contrast, syntax errors prevent the program from running. 

With conditionals, it's better to explicitly call out the most specific case right from the start ot make it more obvious to the reader. (Black jack example)