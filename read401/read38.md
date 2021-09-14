# React 2

## Conditional Rendering

Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.

1. Using an if…else Statement
2. Using a switch Statement
3. Using Element Variables
4. Using Ternary Operators
5. Using Logical && (Short Circuit Evaluation)
6. Using Immediately Invoked Function Expressions (IIFEs)
7. Using Enhanced JSX Libraries

## Lists and Keys

* Following is the way of implementing a list.

import React, { Component } from "react";class List extends Component {
  students = [
    { id: 1, name: "Amal", age: 25 },
    { id: 2, name: "Mark", age: 32 },
    { id: 3, name: "Sithum", age: 28 },
    { id: 4, name: "Tony", age: 30 }
  ];  studentList = this.students.map(student => (
    <Student name={student.name} age={student.age} />
  ));
 
  render() {
    return <div>{this.studentList}</div>;
  }
}const Student = props => {
  return (
    <div>
      <h6>
        {props.name} is {props.age} years old
      </h6>
    </div>
  );
};export default List;

* Keys are used to uniquely identify elements in a list and it helps react to identify what is added, updated and changed. 

Keys must be unique.

## Forms

Handling forms is about how you handle the data when it changes value or gets submitted.

In HTML, form data is usually handled by the DOM.

In React, form data is usually handled by the components.

When the data is handled by the components, all the data is stored in the component state.

You can control changes by adding event handlers in the onChange attribute



Note: You must initialize the state in the constructor method before you can use it.

Note: You get access to the field value by using the event.target.value syntax.

## Lifting State Up

In React, sharing state is accomplished by moving it up to the closest common ancestor of the components that need it. This is called “lifting state up”. 

There should be a single “source of truth” for any data that changes in a React application. Usually, the state is first added to the component that needs it for rendering. Then, if other components also need it, you can lift it up to their closest common ancestor. Instead of trying to sync the state between different components, you should rely on the top-down data flow.

Lifting state involves writing more “boilerplate” code than two-way binding approaches, but as a benefit, it takes less work to find and isolate bugs. Since any state “lives” in some component and that component alone can change it, the surface area for bugs is greatly reduced. Additionally, you can implement any custom logic to reject or transform user input.

## Composition vs Inheritance

* When a child class derives properties from it’s parent class, we call it inheritance. 

* Composition is also a familiar concept in Object Oriented Programming. Instead of inheriting properties from a base class, it describes a class that can reference one or more objects of another class as instances.

## Thinking in React

Process of building a searchable product data table using React:

Start With A Mock 

Step 1: Break The UI Into A Component Hierarchy 

Step 2: Build A Static Version in React 

Step 3: Identify The Minimal (but complete) Representation Of UI State 

Step 4: Identify Where Your State Should Live 

Step 5: Add Inverse Data Flow 


