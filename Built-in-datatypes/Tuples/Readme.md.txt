**Author:** Anagha Sivadas T

***

# Tuples

Tuples are immutable sequences, typically used to store collections of heterogeneous data

Tuples may be constructed in a number of ways:

 *  Using a pair of parentheses to denote the empty tuple: `()`
 *  Using a trailing comma for a singleton tuple: `a,` or `(a,)`
 *  Separating items with commas: `a, b, c` or `(a, b, c)`
 *  Using the `tuple()` built-in: `tuple()` or `tuple(iterable)`

The constructor builds a tuple whose items are the same and in the same order as *iterable*’s items.
 *iterable* may be either a sequence, a container that supports iteration, or an iterator object.
 If iterable is already a tuple, it is returned unchanged.
 For example,
* tuple('abc') returns ('a', 'b', 'c') 
* tuple( [1, 2, 3] ) returns (1, 2, 3).
 If no argument is given, the constructor creates a new empty tuple, ().
