# Branching
Ada Build - Intro to Python: Lesson 3

## Learning Goals
* Understand + use relational operators
* Understand + be able to use conditional statements
* Understand the control flow of a program
* Identify + debug simple logic errors

## Relational Operators

Relational operators allow us to compare two or three values. The objects don't need to be the same type.

The operators:
* equals == 
* does not equal != 
* less than <
* greater than >
* less than or equal to <=
* greater than or equal to >=

Notes:
* In Python, we can use relational operators on all numbers and strings.
* Equals and does not equal can also be used on lists and dictionaries.
* The opposite of > (greater than) is <= (less than or equal to)
* The opposite of < (less than) is >= (greater than or equal to)
*  = is the assignment operator. This is VERY different from == which is the equality operator
*  Relational operators can be chained together like 0 < x <= 100 or 10 > x > 1.

## Boolean Values
* The two possible values of the boolean data type (bool) are True and False
* A non-boolean value that evaluates to False is called "falsey" or "falsy"
  * Sequences and Collections:
    * Empty lists [ ]
    * Empty tuples ( )
    * Empty dictionaries { }
    * Empty sets set( )
    * Empty strings ""
    * Empty ranges range(0)
  * Numbers
    * Zero of any numeric type
      * Integer: 0
      * Float: 0.0
      * Complex: 0j 
  * Constants
    * None
    * False
* A non-boolean value that evaluates to True is also called "truthy"
