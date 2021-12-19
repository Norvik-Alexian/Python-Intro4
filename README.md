# Python-Intro4

## For Loop
* for allows iterating over elements of array
* On each iteration target gets value of next object element

## Iterating List
* We can check if element is in the list
* Going through each element can be done using for in

## List Comprehension Expression
* Comprehension expression consists of brackets containing an expression followed by a for clause, then zero or more for
or if clauses
* Format: [<expression><for clause><for or if clause>]
* The result will be a new list resulting from evaluating the expression in the context of the for and if clauses which
follow it.
* Alternative (simple for vs comprehension)
* To generate new lists based on existing ones we can use comprehension expression

## Timeit
* This module provides a simple way to find the execution time of small bits of Python code.
* Measuring time before and after running method is not precise as there might be a background process momentarily 
running which disrupts the code execution and you will get significant variations in the running time of small code snippts.
* timeit runs your snippet of code millions of times so that you get the statistically most relevant measureent of code
execution time.

## String
* String - is ordered sequence of characters (characters array)
* String type pseudonym is `str`
* By default, strings in Python 3 are encoded using Unicode

## Escape Sequences
* Escape sequences are used to place single quotes in single-quoted string or for double-quoted ones, or for using special
characters
* Escape sequences starts from / symbol
* Sometimes escape sequences are not convenient, to suppress escape sequences we can use r in front string

## If/elif/else
* To check conditions in Python we can use if/elif/else, only if is mandatory elif and else are optional
  * To check multiple conditions we can use `and` and `or` keywords

## Object Methods
* Method - is a function specific for object of some specific type

## Strings Immutability
* By default, Strings in Python are Immutable: Each modification of string creates a new string (not changes the old one)
* Some types in Python are Immutable (Strings, Numbers, Tuples)

## Regular Expressions
* To work with regular expressions we should use external modules, for example, `re`

## Dictionary
* Dictionary - is a collection of <key.value> pairs (mapping from key to value)
* Dictionary element don't have predefined order
* Key can be value of immutable type
* Dictionary can be modified (mutable)
* Dictionary is implemented as hash table (data structured that has high performance on access by key)
* Dictionaries are mutable

## List & Dictionaries
* List - is ordered collection of references to objects
* Dictionary - is unordered collection of references to object supporting access by key.

## Iterating over Dictionary
* We can't predict the order of dictionary elements
* We can get dictionary keys as list and to iterate over them.
* We can sort list of keys or use sorted()

