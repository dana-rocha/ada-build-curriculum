# Programming Grammar
Ada Build - Intro to Python: Lesson 2

## Learning Goals
* Understand + identify different data types
* Assign data to variables
* Use the print function 
* Understand + use string concatenation and string interpolation
* Identify + debug simple errors

## Comments

Comments allow us to leave notes with our code. These notes help use when we return to our code later and anyone else who looks at our code. 
Beginning a line using the `#` character is a comment. Comments are not executed and are ignored when the program is run.

## Data Types 

|  Data Type   |  Description   |   Example  | 
| --- | --- | --- |  
|  string or str  |  A collection of characters within single or double quotes  |   `"hello"` or `'hello'`  | 
|  integer or int |  A number with no decimal  |   `1`, `0` , `- 7`  | 
|  float          |   A real value (decimal)  |   `0.5`, `3.14`  | 
|  list           |  A collection of data of 1+ types within square brackets   |   `["hello", 4, 1.6]`  | 
|  dictionary or dict  |  A set of key, value pairs within curly brackets   |  `{"A": 2, "B":3, "C": 1}`   | 

### Determining the Type
Use the function `type` to determine the object's data type. 

## Classes

* Classes are data along with the operations we can do to that data. 
* Objects are instances of a class
* Almost all data in Python is saved as an object

Example:
* 1 , 2, 3 are instances of the class `int` but instead: `<class 'int'>`
* `hello`, `"good bye"`, `"see ya"` are instances of the class `str`, and the operations we can do include capitalization and concatenation

## Assignment
Variables have a name and a value. We assign a value to a variable name using an assignment statement. 

In programming, we use this to store values because often we want to refer to values later on or to do a calculation. 

Examples assignment statements: `x = 5` or `dog_name = "Raquel"`. 

It can be helpful to read assignment statements right to left like "assign the value 5 to x" or "assign 'Raquel' to dog_name". 

Avoid saying "x equals 5" because that means something different in Python. 

## Mathematical Operations

|  Operation   |  Symbol   |   Example  | 
| --- | --- | --- |  
| Addition | `+` | `2 + 3` |
| Subtraction | `-` | `4 - 5` |  
| Multiplication | `*` | `7 * 8` |  
| Division | `/` | `1 / 2` |  
| Truncation Division | `//` | `1 // 2` |  
| Remainder (Modulus) | `%` | `15 % 5` |  

### Division

Python has two types of division. The first is "regular" division (`/`) where `1/2 = 0.5`. The other is "truncating" division (`//`) where `1//2 = 0`.

In some languages, "integer division" is always truncating. However, in Python 3, `/` always results in a `Float` and `//` always results in an integer. 

### Modulus

Modulus (or "mod) returns the REMAINDER of dividing one number by another number. For example, `15 % 10` will return `5`.

### Precedence

Order of operations! PEMDAS

## Compound Assignment Statements

It is possible to perform an operation and assign a value in the same step.

* Add and assign `+=`
* Subtract and assign `-=`
* Divide and assign `/=` or `//=`
* Multiply and assign `*=`

Example statements:
* `x += 3` assigns the value of `x + 3` to the variable `x`
* `x += y + 3` assigns the value of `x = (y + 3)` to the variable `x`

## Strings

### String Interpolation and Methods

Strings in Python are objects that hold a sequence of characters. They're created by surrounding the sequence of characters with double or single quotes.

Methods are functions that can be called on instances of a class. This is a specific name for a function and are called using parentheses.

String interpolation is the process of substituting values of variables into placeholders in a string.

### Indexing/Slicing

Indexing refers to retrieving a single value from a group, in this case a string of characters, by using it's position in that group. Also, it can refer to the way in which we label those positions. 

* In Python, indexing starts at 0. So, the first character in the string is at index 0.
* Python also uses negative indexing.
