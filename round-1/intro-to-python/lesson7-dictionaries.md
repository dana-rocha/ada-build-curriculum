# Dictionaries
Ada Build - Intro to Python: Lesson 7 

## Overview
Dictionaries are common Python data structure types. They are similar to lists but let us store and retrieve values using integer indices. Dictionaries use key-value pairs. 

Dictionaries are useful when we need to organize data in a way that makes it easy to look up a certain key like a person's name or a product code. 

### Dictionaries with Data
Dictionaries are initialized using curly braces {} or the dict() function. The data in a dictionary consists of key-value pairs. Each key-value pair in a dictionary is referred to as an item. 

The order of the key-value pairs is not guaranteed so a dictionary is a collection of unordered items.* 

* However, starting from Python 3.7, insertion order of Python dictionaries is guranteed. BUT we shouldn't soley rely on them!!!

Sources: 
* https://www.geeksforgeeks.org/ordereddict-in-python/
* https://softwaremaniacs.org/blog/2020/02/05/dicts-ordered/


### Accesssing Values
Once a dictionary is created, we can access a value in that dictionary by using square brackets [] to specify a key. We can also use square brackets with a key to store a new value for the key. 

## What can be used as keys?
Any type of object can be used as a value but dictionaries can only use immutable types as keys. (types that can mutate or change) 

Therefore, we can use an int, str as a key. But, we can't use a list or another dictionary for keys. 

## Using Built-in Methods and Functions
Dictionaries are represented by the built-in Python type dict. Here are some important methods the dict type provides. 
### .get(arguments)

The .get method behaves similarly to the square bracket [] syntax for retrieving the value of a specified key. 

The advantage of using .get over the square brackets is that if the key doesn't exist, Python will return None as the default value, while with square brackets [], Python will raise an error. 

A second argument to .get can be provided if we need some other value other than None. 

### .keys()
The .keys method returns a view object that can be used to iterate over the keys of a dictionary. 

REMEMBER: it returns a view of the dictionary's keys, NOT a list --> we can't access individual elements like a list

You CAN iterate through the keys with a for loop or convert the keys into a list using the list function. 

However, once you conver the view into a list, it won't be connected to the original dictionary. 

### .values() 
Similar in use to the .keys method, we can use the .values method to get a view object with which we can iterate over the values of the dictionary. 

### .pop()
Use the .pop dictionary method to remove a dictionary key. It will also return the value that was stored at the key. 

## Looping Over a Dictionary
We can use a for loop to iterate over a dictionary, similar to how we can iterate over a list. However, while list iteration updates the loop control variable with the list values, dictionary iteration will give us the keys. 

Dictionaries don't guarantee to maintain the items in order. 

https://docs.python.org/3/tutorial/datastructures.html?highlight=lists#looping-techniques

## Dictionaries vs. Lists

### Similarities
* Store collections of data
* Allow access to individual elements via a key or index
* Allow the collection to be iterated through

### Differences
* Lists maintain elements in ordinal iteration order (aka sequencial order)
* Dictionaries don't maintain ordered
* Lists use integer indices to access specific elements --> Dictionaries use any immutable data type as a key