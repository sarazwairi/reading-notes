# Random Module in Python

## We want the computer to pick a random number in a given range Pick a random element from a list, pick a random card from a deck, flip a coin etc. When making your password database more secure or powering a random page feature of your website.

### Randint

```
import random
print random.randint(0, 5)
```

### Random

```
import random
random.random() * 100
```

### Choice

```
random.choice( ['red', 'black', 'green'] ).

The choice function can often be used for choosing a random element from a list.

import random
myList = [2, 109, False, 10, "Lorem", 482, "Ipsum"]
random.choice(myList)
```

### Shuffle

```
from random import shuffle
x = [[i] for i in range(10)]
shuffle(x)

Output:
# print x  gives  [[9], [2], [7], [0], [4], [5], [3], [1], [8], [6]]
# of course your results will vary
```

### Randrange

```random.randrange(start, stop[, step])

import random
for i in range(3):
    print random.randrange(0, 101, 5)
```

# What is Risk Analysis in Software Testing and how to perform it?

risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test. 

## Why use Risk Analysis?

using risk analysis at the beginning of a project highlights the potential problem areas.

## Risk Identification

* Business Risks
* Testing Risks
* Premature Release Risk
* Software Risks

## Risk Assessment

There are three perspectives of Risk Assessment:

   * Effect

   * Cause

   * Likelihood



## How to perform Risk Analysis?
   * Searching the risk

   * Analyzing the impact of each individual risk

   * Measures for the risk identified

# Big O Notation

We use big-Θ notation to asymptotically bound the growth of a running time to within constant factors above and below. Sometimes we want to bound from only above. 


