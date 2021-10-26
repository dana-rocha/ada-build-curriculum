# Dictionaries
Ada Build - Intro to Python: Lesson 7

A Dictionary is another common Python collection type. Compared to lists, dictionaries allow us to use a wider variety of data types.

Dictionaries are useful when we need to organize data in a way that makes it easy to loop up by a certain key such as a person's name or maybe a product code. 

Dictionaries use curly braces `{}` and like with lists, we can create an empty dictionary or one with data.

The data in a dictionary consists of key-value pairs. Each key-value pair in a dictionary is referred to as an item. 

Dictionaries are NOT ORDERED. It's a collection of unordered items!!

Access a value in a dictionary by using the square brackets `[]` to specify a key. ALso use square brackets with a key to store a new value for that key.

## What can be a key?

Any immuntable object can be a key. This means integers or strings can be keys. 

## Built-in Methods and Functions

### `.get(arguments)`

When given a single argument, `.get` acts similarly to the square bracket syntax for retrieving the value of a specified key.

### `.keys`

To iterate over the keys of the dictionary

### `.values`

To iterate over the values of the dictionary

### `len()`

Can use the `len` function to get the number of items in the dictionary

## Looping over a Dictionary

Can use a `for` loop to iterate over a dictionary similar to how we can iterate over a list. However, list iteration updates the iteration vairable with the list values whereas dictionary iteration will give us the keys.

## Remove Values from a Dictionary

Remove a key-value pair with `.pop`

## Dictionaries vs. Lists

Similarities: 
* Both store collections of data
* Both allow access to individual elements via a key or index
* Both allow the collection to be iterated through

Differences:
* Lists maintain elements in ordinal iteration order --> dictionaries are unordered
* Lists use integer indices to access specific elements --> dictionaries can use any immutable data as a key

## Vocabulary

1. Data structure - a collection of data organized according to some principles and operations that can be applied to that data

2. Key-value pair - a set of two linked data items. The key is used to retrieve its linked value

3. Dictionary - a data structure that stores a collection of key-value pairs with each key-value pair mapping the key to its associated value

## Nested Dictionaries

We can store dictionaries inside lists or even dictionaries inside other dictionaries - in order to represent more complex relationships within our data. 

