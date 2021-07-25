# In Tests We Trust — TDD with Python

Unit tests : are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

AAA: Arrange, Act and Assert.

## The Cycle

by three steps:

🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)

✅ Write the feature and make the test pass! (you can dance after that)

🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

# What does the if __name__ == “__main__”: do?

If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 

# Recursion

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.

### In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems.

### difference between direct and indirect recursion

```// An example of direct recursion
void directRecFun()
{
    // Some code....

    directRecFun();

    // Some code...
}

// An example of indirect recursion
void indirectRecFun1()
{
    // Some code...

    indirectRecFun2();

    // Some code...
}
void indirectRecFun2()
{
    // Some code...

    indirectRecFun1();

    // Some code...
}```

