# Advanced Operations with Functions in Python

# Python Variable Scope
purpose is to know where and where not a variable is accessible from
Variables are only accessible within their scope - Global/Local
Variables defined in a function are only accessible within that function -local
Variables defined outside of a function - global
a caveat to this is a variable inside a function with keyword 'global' will be scoped globally

# Yielding Python Functions

a type of generator function
Yield replaced 'return' and creates a sequence of results
temp suspends function execution
returns to suspended point, remembering 'state'
Is used to produce iterable results from a function

iterable results can be looped through with a for loop

The next() function steps through the generator function and returns the results a single step at a time

# Mapping Filtering and Reducing

operate on a set of data without iterables/looping

Functional programming relies on manipulating sets of data instead of iterating through data
 - requres special functions that operate functionally
 - Three common techniques - Mapping, Filtering, and Reducing

Mapping - apply a transformation to each item
Filtering - Limit the number of items
Reducing - Summzarize elements as a single value. requires import of functools

These allow the computer/pyton interprate to figure out the best way to go through data

# Sorting Functions

Sorted and Sort are two functions to sort an iterable list. Only works on list meaning doesn't work with tuples(unmuttable) and sequences(not ordered)
Sorted works with str text
Key is a sorting parameter that allows ou to change what value is used to sort
