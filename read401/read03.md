# FileIO & Exceptions

## What Is a File?

At its core, a file is a contiguous set of bytes used to store data. This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable. In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.

composed of three main parts:

* Header: metadata about the contents of the file (file name, size, type, and so on)

* Data: contents of the file as written by the creator or editor

* End of file (EOF): special character that indicates the end of the file

## Opening and Closing a File in Python

```reader = open('dog_breeds.txt')```

```with open('dog_breeds.txt') as reader:```

## Reading 

 There are multiple methods that can be called on a file object to help you out:

* .read(size=-1)

* .readline(size=-1)

* .readlines()

## Python Exceptions: An Introduction

### Exceptions versus Syntax Errors

* Syntax errors occur when the parser detects an incorrect statement

* exception error. This type of error occurs whenever syntactically correct Python code results in an error. 

### Raising an Exception

We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.

### The AssertionError Exception

Instead of waiting for a program to crash midway, you can also start by making an assertion in Python. We assert that a certain condition is met. If this condition turns out to be True, then that is excellent! The program can continue. If the condition turns out to be False, you can have the program throw an AssertionError exception.

### The try and except Block: Handling Exceptions

The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.

