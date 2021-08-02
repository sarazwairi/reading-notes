# Game of Greed 3

## List Comprehensions in Python

List comprehensions provide a concise way to create lists.

The list comprehension always returns a result list.

```
[ expression for item in list if conditional ]
```

## Examples:

* Create a simple list

```
x = [i for i in range(10)]
print x

# This will give the output:
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```

* Create a list using loops and list comprehension

```
# You can either use loops:
squares = []

for x in range(10):
    squares.append(x**2)
 
print squares
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

# Or you can use list comprehensions to get the same result:
squares = [x**2 for x in range(10)]

print squares
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

* Multiplying parts of a list
* Show the first letter of each word
* Lower/Upper case converter
* Print numbers only from a given string
* Parsing a file using list comprehension
* Using list comprehension in functions