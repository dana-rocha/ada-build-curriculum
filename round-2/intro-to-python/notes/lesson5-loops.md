# Loops and Iterators
Ada Build - Intro to Python: Lesson 5

## Loops 

Loopers are programming constructs that help us repeat code for a certain number of times without needed to copy and paster the code.

Iteration also means looping. 

## Types of Loops

There are 2 categories of loops: counter-controlled and sentinel-controlled loops

1. Counter-controlled loops are used when the numebr of loops can be determined before loop execution
2. Sentinel-controlled loops are used when the number of loops cannot be determined before loop execution

## `for` loop

We use a `for` loop with a specific `range(n)` to run the code in its block `n` times.

The range function returns a sequence of numbers from 0 to n-1.

A `for` loop can also be used to iterate over characters in a string or elements in a list. This loop is called a for-each loop in some programming languages.

## `while` loop

The `while` loop is useful when you want to continue an action while a certain condition is `True` but we may not know how many times we'll need to do that action. This is an example of a sentinel-controlled loop. As soon as the condition stops being `True`, the loop will terminate. 

It's helpful to read that condition and the while loop as "while condition is true do x"

## Vocabulary

* Iteration variable: A variable created by the loop to either track the number of times the loop has executed or the current element of a container
* Sentinel controlled loop: A loop that's controlled by the truthiness of a variable or conditional expression
