# Writing a Function in JavaScript

![Breakfast for Coders](https://images.unsplash.com/photo-1482049016688-2d3e1b311543?q=80&w=3110&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.


## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
greet('Alice'); // Outputs: Hello, Alice!
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

