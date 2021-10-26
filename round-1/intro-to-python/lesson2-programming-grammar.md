# Programming Grammar 
Ada Build - Intro to Python: Lesson 2

## Data Types
* String (str) = A collection of characters within single or double quotes
* Integer (int) = A number with no decimal
* Float = Real value (decimal)
* List = A collection of data of one or more types within square brackets
* Dictionary (dict) = A set of key-value pairs 

To determine the type of an object, we use the function type(). We can call the this function on a literal value such as the integer 3 or string "hello", or a variable that holds a value. 

In Google Colab, the result from the last line of a code block is printed to the screen.

### What is a class? 
When this code block is executed:
print(type(1))

The output is: <class 'int'>

Classes are data along with the operations we can do to that data. 
Objects are instances of a class. 

For example: 1, 2, 3 are instances of the class int and the operations we can do are math operations. 
Another example: "hello", "good bye", and "see ya" are instances of the class str and the operations we can do include capitalization and concatenation. 

Almost all data in Python is saved as objects. 
## Mathematical Operations
* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Truncation Division (//)
* Remainder (modulus) (%)

Order of operations or precedence determines in which order the operations are completed. 

### Division
Python has two types of division. The first is "regular" division (/) where 1/2 = 0.5. The second is "truncating" division (//) where 1//2 = 0. 

In some languages, integer divition is always truncating. This was true for old versions of Python but in Python 3, / always results in a Float and // always results in an integer.
### Modulus 
Modulus or mod returns the remainder of dividing one number by another number. For example, 15 % 10 = 5. 

## Assignment Statements
In programming, we often need to store values and we may want to refer to the values later. We use variables to store values and communicate intent. 

Variables have a name and a value. We assign a value to a variable using an assignment statement. 

It's helpful to read assignment statements right to left like "assign the value 5 to x" or from left to right like "set the variable x to 5". 

Avoid saying things like "equal" or "equals" because that means something different when it comes to Python. 
### Compound Assignment Statements
It's possible to perform an operation and assign a value all in the same step. 
For example, to add and assign we can use +=. To subtract and assign we can use -=. 
Similarly, to divide and assign, we can use /= or //=. To multiply and assign we can use *=. 

Examples:
* x += 3 assigns x + 3 to x
* x += y + 3 assigns the value of x + (y + 3) to the variable x
* x -= 2 assigns the value of x - 2 to the variable x
* x -= y - 5 assigns the value of x - (y -5) to the variable x
* x /= 3 assigns the value of x / 3 to the variable x
* x //= 3 assigns the value of x // 3 to the variable x
* x *= y assigns the value of x * y to the variable x
* x %= y assigns the value of x % y to the variable x

## Strings
### String Interpolation and Methods
Strings in Python are objects that hold a sequence of characters. We can create a string by surrounding the sequence of characters with double or single quotes. 

Methods are functions that can be called on instances of a class. It's a more specific name for a function and are called using parentheses (). 

String interpolation is the process of substituting values of variables into placeholders in a string. 

Example: 
```print(f"True or False? The value {value_1} is a digit: {value_1.isdigit()}")```

Notice how in the example above, the string with interpolation can be contained in single or double quotes. The value to be interpolated is placed within curly braces {} and the character f is written in front of the string. The f in the string interpolation is short for "format".
### Common Escape Sequences
The escape character \ invokes different meanings. 

| Escape sequence |  Description       |
| :-------------: | :-------------:    |
|    \n           | A new line         |
|    \\           | A single backslash | 
|    \"           | A double quote     |
|     \'          | A single quote     |
|       \         | Allows a string to wrap to the next line |