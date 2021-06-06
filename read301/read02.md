# State and Props

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

2. What is the very first thing to happen in the lifecycle of React?

Constructor

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

* constructor
* render
* React Updates
* componentDidMount
* componentWillUnmount

4. What does componentDidMount do?

its sub-components have rendered properly

# React State Vs Props

1. What types of things can you pass in the props?

can be anything (integers , objects ,arrays)

2. What is the big difference between props and state?

props are like arguments to functions, pass into a component which means it is handled outside the component and must be updated outside the component

state :sth inside a component ,is handle inside the coponent and must be updated inside the component

3. When do we re-render our application?

the user makes a change

4. What are some examples of things that we could store in state?

numbers,strings,boolean,array,objecys