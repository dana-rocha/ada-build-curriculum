# Loops and Iteration
Ada Build - Intro to Python: Lesson 5

## Loops
Loops are programming constructs that help us repeat a code action for a certain number of times. This is based on algorithmic logic and removes the need of having to copy and paste code. 

Another term for looping is iteration. 

All high-level programming languages provide various forms of loops, which can be used to execute one or more statements repeatedly. 

## Types of Loops

Two broad categories of loops: Counter-controlled and sentinel-controlled loops 
### Counter-controlled Loops
This type of loop is more clear and less error prone. They're used when the number of loops can be determined prior to loop execution. 

An example of a counter-controlled loop is wanting to print your name out 10 times. 

### Sentinel-controlled loops
This type of loop is used when the number of loops cannot be determined prior to loop execution. 

An example of a sentinel-controlled loop is a program that asks the user if the user would like to continue playing a guessing game. Based on comparing the user input value, the program determines whether to continue or exit the loop. 

### for (range)
We use a for loop with a specific range(n) to run the code in its block n times. 

The range function returns a sequence of numbers. If we give it one argument, called n, the range function will give us a sequence from 0 to n-1. In mathematical range notation, this is expressed as [0, n). 

So, range(5) will give us numbers 0, 1, 2, 3, 4.

### for (string)
A for loop can also be used to iterate over the characters in a string or the elements in a list. This is often called a for-each loop in other programming languages. 