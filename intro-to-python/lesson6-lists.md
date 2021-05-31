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

Index values start at zero. 

Slicing lists is very similar to slicing with strings. 

Examples: 
* list[i] --> gets a single element
* list[i:j] --> gets a list of elements from index i to j-1
* list[i:j:k] --> gets a list of elements from index i to j-1, stepping by the interval k

### Data Assignment
We can assign and reassign values in lists. We can use list indexing to see what object is regerenced at a particular location. We can also update a particular location to refer to a different object also using list indexing. 

## Built-in Methods
Lists have many bult-in functions and methods including the len function and method append.