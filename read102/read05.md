# Comparison Operators

Conditions can be evaluated using comparison operators. The result of such expression will be a boolean: true or false.

- Is equal to ```==``` compares two values to check if they are the same

- Is not equal to ```!=``` compares two values to check if they are not the same

- Strict equal to ```===``` compares two values to verify that both the value and the data type are the same

- Strict not equal to ```!==``` compares two values to verify that both the value and the data type are different

- Greater than:  ```4 > 2``` returns true

- Less than: ```1 < 3``` returns true

- Greater than or equal to ```>=```

- Less than or equal to ```<=```

## Logical Operators

These operators can be used to return the result of multiple comparison operators

```((5 < 2) && (4 >= 3))```

- Logical AND ```&&```

- Logical OR ```||```

- Logical NOT ```!```

## Loops

A loop is block of code that will keep running as long as the condition is true. The most common types of loops are:

- For loop; used when the code has to run specific number of times. It uses a counter as a condition

- While loop; used when the number of repetitions is unknown

- Do while loop; the fundamental difference between this loop and while loop is that the code will run at least once even if the condition evaluates to false

A for loop consists of variable initialization, condition, and update

```for (var i = 0; i < 5; i++)```

An example of while loop which stores 5 times table in a variable

```JavaScript
var i = 1;
var msg = '';

while (i < 10) {
    msg += i + ' x 5 = ' + (i * 5) + '<br />';
    i++;
}
document.getElementById('answer').innetHTML = msg;
```
