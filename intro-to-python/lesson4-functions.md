# Functions 
Ada Build - Intro to Python: Lesson 4

Functions are basically input and output machines. Basically, they take an argument as input and return a value as output. 

## Built-in Functions
* str() converts data to the string class
* int() converts data to the integer class
* float() converts data to the float class
* abs() returns the absolute value of the value
* round() returns the value rounded to the nearest integer
* input() accepts user input

## Modules
Python provides some built-in modules that contain additional functions. 
Common Python modules include the math module and the random module. Module are commonly called libraries.

### Range Notation
The range of [0.0, 1.0) is the mathematical notation (not Python notation) for a range that starts at 0.0 continuing up to, but excluding 1.0. It is inclusive on the lower bound but exclusive on the upper. This means that 0.0 is included in the range but 1.0 is not. 

Mathematical notion:
* Brackets [a, b] = indicates inclusion of a bound in a range
* Parentheses (a, b) = indicates exclusion of a bound from a range

Again, mathematical notion NOT Python notation but it might come up in documentation.

## Defining Functions
Functions allow us to assign a name and structure to sections of code. A function is made up of two parts: the name of the function and the parameters it expects. Once we have defined those two things, we can create a def (function) block. 

To call a function, you need parentheses: my_function()
If you leave the parentheses off, Python will give you the reference of the function.

### Function Arguments (and Parameters)
Most people use argument and parameter interchangably. Here's the difference:

In most programming languages, including Python, parameters are variables used to refer to the pieces of data provided as input to a function while arguments are those pieces of data passed to the function when it gets called. The parameters are defined in the function signature and the arguments are specific values given to the function when it's invoked. 

### None
A function does NOT need to return a value. If a function doesn't return a value, the return value will be set to None. 

## Vocabulary

* Function = A section of code with a name
* Function Signature = The name and parameters of a function
* Return = Immediately exit a function. Can also send a result back to where it was called. If no result is supplied, the returned value will be None. 
* Invoke = Run a function or calling a function
* Argument = The value to be used for a particular parameter. Specified when the function is invoked. 

