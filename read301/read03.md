# Passing Functions as Props

## React Docs - lists and keys

* What does .map() return?

a map object , which is an iterator that yields items on demand

* If I want to loop through an array and display each value in JSX, how do I do that in React?

```const elements=[]//..some array const items=[]for (const[index,value]of elemenets.entries()){items.push(<Element key={index}>/>)}```

* Each list item needs a unique key.

* What is the purpose of a key?

is an inset on a map that explains the symbols, provides a scale , and usually identifies the type of map projection used spread operator.

## The Spread Operator

* What is the spread operator?

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

* List 4 things that the spread operator can do.

Copying an array
Concatenating or combining arrays
Using Math functions
Using an array as arguments

* Give an example of using the spread operator to combine two arrays.

const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍

* Give an example of using the spread operator to add a new
item to an array.


const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

* Give an example of using the spread operator to combine two objects into one.


const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

## How to Pass Functions Between Components

* In the video, what is the first step that the developer does to pass functions between components?

creat te function where is the state we gona change.

* In your own words, what does the increment function do?

determines the next node at the same level. You can also increase the level of a node by one at a specified level.

* How can you pass a method from a parent component into a child component?

by using props 

* How does the child component invoke a method that was passed to it from a parent component?

(i didnt get that point )

## Things I want to know more about(n/a)
