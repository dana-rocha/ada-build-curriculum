# Lists
Ada Build - Intro to Python: Lesson 6

Lists are the most common data type used to create collections in Python. 
A `list` is an ORDERED collection of objects enclosed by square brackets `[]`.

List Example: `[1, 10, 33, 50, 2, 7]`

To create a list, you can start with an empty one or a list with an initial set of values. 

Python lists can store all sorts of data and it's not a requirement that all items stored to be of the same type. However, it's best to keep the list items as one type to avoid confusion. 

## Indices

We can index a `list` using square brackets `[]` to retrieve a value just like how we can index a `string` with square brackets `[]` to retrieve a character.

Indexing starts at zero!!

### Slicing and Negative Indices

Slicing with lists is very similar to slicing with strings. 
* `list[i]` - gets a single element
* `list[i:j]` - gets a list of elements from index `i` up to but not including index `j` 
* `list[i:j:k]` - gets a list of elements from index `i` up to but not including index `j`, stepping by the interval `k`

Python lists also supports negative indexing. 

Like with string replication, lists can be replicated too

String Replication: `s = "abc" * 5`
List Replication: `zeros = [0] * 5`

## Data Assignment

Lists allow us to assign and reassign their values.

Each location in a list acts like its own variable. We can use list indexing to see what object is referenced at that particulation. We can also update a particular location also using list indexing.

## Built-in Methods

List is a built-in class in Python and it has many built-in functions and methods such as `len` and `append`

## Looping over a List

### `for` loops and `range`

The `len` and `range` functions can be utilized with a `for` loop to retrieve the value of each element in a list. 

### `for` directly on a list

Python also lets us use a `for` loop to retrieve each item directly from lists and other collections. This is commonly known as a `for-each` loop in other programming languages.

