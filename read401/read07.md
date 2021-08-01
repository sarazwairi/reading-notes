# Game of Greed 2

## Modules: The Global Scope

Python turns your program’s main script into a module called __main__ to hold the main program’s execution. The namespace of this module is the main global scope of your program.

### Whenever you assign a value to a name in Python, one of two things can happen:

* You create a new name
* You update an existing name

### Modifying global names is generally considered bad programming practice because it can lead to code that is:

* Difficult to debug: Almost any statement in the program can change the value of a global name.
* Hard to understand: You need to be aware of all the statements that access and modify global names.
* Impossible to reuse: The code is dependent on global names that are specific to a concrete program.

## The nonlocal Statement

nonlocal names can be accessed from inner functions, but not assigned or updated. If you want to modify them, then you need to use a nonlocal statement. With a nonlocal statement, you can define a list of names that are going to be treated as nonlocal.

The nonlocal statement consists of the nonlocal keyword followed by one or more names separated by commas. 