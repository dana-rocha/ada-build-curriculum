# Functions
Ada Build - Intro to Python: Lesson 4

## Learning Goals
* Use common built-in functions in Python
* Understand + use functions contained in modules
* Write + use custom functions
* Understand + define:
  * docstring
  * signature
  * arguments
  * parameters
  * return
* Understand the results of an `AssertionError`

## Built-in Functions

Functions are basically input/output machines. They take an argument in as input and return a value as output.

Common built-in functions include: `bool`, `type`, `str`, `int`, `float`, `abs`, `round`, `input`

## Modules

Python has some built-in modules that contain additional functions. 
Modules allow related code to be grouped together so that the code is easier to understand and use. It also helps make the code more logically organized. 

Common Python modules: `math`, `random`

### Range Notation in Math

* inclusivity/exclusivity in math:
  * 1 to 10 inclusive = [1, 10] 
    * can remember that because bracket looks like its including the 10 
  * 1 to 10 exclusive = [1, 10)
 
* INCLUsive --> INCLUding the last number
* EXCLUsive --> EXCLUding the last number

## Defining Functions

Functions allow us to assign a name and structure to sections of code. We can create functions when there are sections of code we may want to reuse, test, customize, and execute independently from other sections of code

### Signatures and Blocks

A function signature has two parts: the name of a function and the parameters it's expecting.

Parentheses (after the function name) are required to call a function and invoke it. A function name without the parentheses only referse to the function. 

### Function Arguments (and parameters)

Most folx use argument and parameter interchangeably which is fine.

In most programming languages (including Python), parameters are variables used to refer to pieces of data provided as input to a function.

Arguments are those pieces of data that are passed to the function when it gets called. 

The parameters are defined in the function signature and the arguments are teh specific values given to the function when it's invoked. 

### docstrings

Lines of code below the function definition. It provides information about what a function does - particularly its inputs and output. 

Access the docstring by using the `__doc__` method. For example, `function_name.__doc__`. Helpful when trying to figure out how to use an unfamiliar funciton

### None

A function does not need to `return` a value! 

If a function doesn't return a value, the return value will be set to `None`.



