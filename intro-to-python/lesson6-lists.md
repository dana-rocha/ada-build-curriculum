# Lists
Ada Build - Intro to Python: Lesson 6

## Overview & Creating Lists
Lists are the most common data type used to create collections in Python. 

A list is an ordered collection of objects that is enclosed by square brackets []. Just like any other data type, a list can be assigned to a variable.

You can create lists that start out empty or lists with an initial set of values. 

### Data Types
Python lists can store all sorts of data including integers, floats, and strings. It's not a requirement that all items stored in a list should be the same type but lists with data of mixed-types would make our code more difficult to understand. 

### Indices
We can index into a list using square brackets [] to retrieve a value, just like how we can index into a string with square brackets [] to retrieve a character. 

Index values start at zero - just like with strings. 

Slicing lists is very similar to slicing with strings. 

Examples: 
* list[i] --> gets a single element
* list[i:j] --> gets a list of elements from index i to j-1
* list[i:j:k] --> gets a list of elements from index i to j-1, stepping by the interval k

### Data Assignment
We can assign and reassign values in lists. We can use list indexing to see what object is regerenced at a particular location. We can also update a particular location to refer to a different object also using list indexing. 

## Built-in Methods
Lists have many built-in functions and methods including the len function and method append.

Recall: 
functions are invoked with the syntax: function_name(arguments)
Methods are invoked with the syntax: object.method_name(arguments)

A method is what we call a function associated with a specific instance of a class. 

## Looping over a list
Loops or iterators working together with lists

### for loops and range
The range function begins counting at 0 and the index of the first element in a list is also 0. We can combine this knowledge and utilize the built-in function len to get the count of elements in a list to retrieve the value of each element in a list. 

## Errors
A common error that is encountered when working with lists is an IndexError. 

