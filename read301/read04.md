# React and Forms

## React Docs - Forms

* What is a ‘Controlled Component’?

is one that takes its current value through props and notifies changes through callbacks like onChange 

* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we update the state with their responses as soon as they enter them because because you need to write an event handler for every way your data can change and It is used controlled component.

* How do we target what the user is entering if we have an event handler on an input field?

you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.


## The Conditional (Ternary) Operator Explained

* Why would we use a ternary operator?

Because it shorten your if statements into one line of code with the conditional operator

* Rewrite the following statement using a ternary statement:

```if(x===y){
  console.log(true);
  } else {
 console.log(false);
  }
  ```
 x===y ? console.log(true) : console.log(false);
 
## Things I want to know more about (n/a)



