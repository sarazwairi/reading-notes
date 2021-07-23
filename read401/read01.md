# Pain vs. Suffering

## pain:

any grpwth will cause pain.

401 level tests a students skills in :

•	Problem solving .
•	Emotional resilience.
•	Research.
•	Collaboration.
•	Outside comfort zone.
•	Physical exhaustion.

## Suffering:

Pain without a gain or goal and depend on perspective.

To gai perspective think about :

1.	What’s your perspective?
2.	Why are you doing this?
3.	Do you want what comes at the end of this journey?
4.	Are you doing this for you?

# A beginner's guide to Big O Notation

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm.

some common orders of growth along with descriptions and examples:

* O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

```
bool IsFirstElementNull(IList<String> elements)
{
    return elements[0] == null;
}
```

* O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. 

```
bool ContainsValue(IEnumerable<string> elements, string value)
{
    foreach (var element in elements)
    {
        if (element == value) return true; 
    }     
    return false; 
}
```

* O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set. 

```
bool ContainsDuplicates(IList<string> elements)
{
    for (var outer = 0; outer < elements.Count; outer++) 
    {
        for (var inner = 0; inner < elements.Count; inner++) 
        { 
            // Don't compare with self 
            if (outer == inner) continue;             
            
            if (elements[outer] == elements[inner]) return true; 
        }
    }    
    return false;
}
```

* O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set.

```
int Fibonacci(int number)
{
    if (number <= 1) return number;
       
    return Fibonacci(number - 2) + Fibonacci(number - 1); 
}
```

# Logarithms

Logarithms are slightly trickier to explain so I’ll use a common example:

Binary search is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value.

Facts and Myths about Python names and values

•	Names and Values in Python
•	Python is a very approachable language.
•	Underlaying mehanisms are often qyite simple but their combined effects might not be what you expect.
•	Local names in the function are drawn in new frame .

### Refrences:
June 2009-A beginner's guide to Big O Notation - Rob Bell (rob-bell.net)

