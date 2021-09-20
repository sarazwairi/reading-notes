# Pythonisms

Dunder or magic methods in Python are the methods having two prefix and suffix underscores in the method name. Dunder here means “Double Under (Underscores)”. These are commonly used for operator overloading. Few examples for magic methods are: __init__, __add__, __len__, __repr__ etc.

    __sub__ for subtraction(-)

     
    __mul__ for multiplication(*)

     
    __truediv__ for division(/)

     
    __eq__ for equality (==)

     
    __lt__ for less than(<)

     
    __gt__ for greater than(>)

     
    __le__ for less than or equal to (≤)

     
    __ge__ for greater than or equal to (≥)


## Python Iterators

Iterator in python is an object that is used to iterate over iterable objects like lists, tuples, dicts, and sets. The iterator object is initialized using the iter() method. It uses the next() method for iteration.
 

    __iter(iterable)__ method that is called for the initialization of an iterator. This returns an iterator object
    next ( __next__ in Python 3) The next method returns the next value for the iterable. When we use a for loop to traverse any iterable object, internally it uses the iter() method to get an iterator object which further uses next() method to iterate over. This method raises a StopIteration to signal the end of the iteration.

## What Are Python Generators?

Python generators are a simple way of creating iterators. All the work we mentioned above are automatically handled by generators in Python.

Simply speaking, a generator is a function that returns an object (iterator) which we can iterate over (one value at a time).

It is fairly simple to create a generator in Python. It is as easy as defining a normal function, but with a yield statement instead of a return statement.

If a function contains at least one yield statement (it may contain other yield or return statements), it becomes a generator function. Both yield and return will return some value from a function.

The difference is that while a return statement terminates a function entirely, yield statement pauses the function saving all its states and later continues from there on successive calls.