# keys
## What does .map() return?
 the map() function is most commonly used for rendering a list of data to the DOM. ... The map() function also takes in an optional second argument, which you can pass to use as this inside the callback. Each time the callback executes, the returned value is then added to a new array
## If I want to loop through an array and display each value in JSX, how do I do that in React?
Use the .map() method to render data.
Parse and display data in an array of objects

## Each list item needs a unique ____.
ul
among their siblings
## What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

# separator operator
## What is the spread operator?
a new addition to the set of operators in JavaScript ES6
## List 4 things that the spread operator can do.
Copying an array.
Concatenating or combining arrays.
Using Math functions.
Using an array as arguments.
## Give an example of using the spread operator to combine two arrays.
const arr1 = [1,2,3]
const arr2 = [4,5,6]
const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6]
## Give an example of using the spread operator to add a new item to an array.
function sum(x, y, z) {
  return x + y + z;
}

const numbers = [1, 2, 3];

console.log(sum(...numbers));
// expected output: 6

console.log(sum.apply(null, numbers));
// expected output: 6
## Give an example of using the spread operator to combine two objects into one.
Use a spread operator ( ...)
Use the Object.assign() method


##  what is the first step that the developer does to pass functions between components?
create the action in the parent component 
## In your own words, what does the increment function do?
It takes a variable and increments (changes) its value, and also returns this value. The increment can be a positive or negative number.
## How can you pass a method from a parent component into a child component?
import React from "react";export default function Child({data, onChildClick}) { return ( <div className="child"> ...
import Child from './Child'
import React from "react"; import "./styles.css";
### How does the child component invoke a method that was passed to it from a parent component?
First off, let me express that this is generally not the way to go about things in React land. Usually what you want to do is pass down functionality to children in props, and pass up notifications from children in events