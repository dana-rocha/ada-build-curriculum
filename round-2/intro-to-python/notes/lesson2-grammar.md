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
* Almost all data in Pyuthon is saved as an object

Example:
* 1 , 2, 3 are instances of the class `int` but instead: `<class 'int'>`
* `hello`, `"good bye"`, `"see ya"` are instances of the class `str`, and the operations we can do include capitalization and concatenation
