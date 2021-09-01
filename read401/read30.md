# Hash Tables

## What is a hash table in python?

Hash tables are a type of data structure in which the address or the index value of the data element is generated from a hash function. 

## Why do we use them?

Used to store keys/value pairs.

## Example:

```
h(k) = k1 % m
```

## Collision

A collision occurs when the algorithm generates the same hash for more than one value. 

## Complexity Analysis

Hash tables have an average time complexity of O (1) in the best-case scenario. The worst-case time complexity is O(n). The worst-case scenario occurs when many values generate the same hash key, and we have to resolve the collision by probing.

## Internal Methods

add()

Find()

Contains()

GetHash()



