# Writing a Function in JavaScript

**In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.**

## 1. Basic syntax

```js
const functionName = (params) => {
  // code to be executed
}
```
**const:** const should be used whenever a function expression is assigned to a variable.

**The function name:** The name you choose for the function.

**Parameters:** Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.

**The arrow syntax:** Indicates that this will be a function.

**The body:** The statements that make up the function itself. Surrounded by curly braces.

**Example:**
```js
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

**Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ).**

## 2. Calling a function

**To execute the function, you call or invoke it by using its name followed by parentheses.**

**Example:**
```js
greet('Alice'); // Outputs: Hello, Alice!
```
## 3. Return values

**Functions can process data input and output a value using the return keyword.**

**Example:** 
```js
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```
**For more information about my son click.**


[About My Son](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

![This is my chiled!!!!](https://www.aap.org/contentassets/01026ca111c248cf82cd0bb47d0239b4/2025-aap-safe-sleep-image-library-165.jpg)
