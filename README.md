## 1. Hello! JavaScript
Print 'Hello, World!' to console.
```javascript
console.log("Hello, World!");
console.log("I'm Sanzu");
```
**Run the program:**
```
hello.js
```
**Output:**
```
console.log("Hello, World!");
console.log("I'm Sanzu");
```
---
## 2. Addition
A simple JavaScript program demonstrating variable assignment and arithmetic operations.

**Features:**
- Declares two constant variables with values 10 and 20
- Calculates their sum using the addition operator
- Displays the result using `console.log()`

```javascript
const num1 = 10;
const num2 = 20;
const sum = num1 + num2;
console.log("The sum is: " + sum);
```
**Output:**
```
The sum is: 30
```
### Function-Based Addition
A JavaScript program showcasing function declaration and reusable code patterns.

**Features:**
- Defines a reusable `addNumbers(a, b)` function
- Accepts two parameters and returns their sum
- Demonstrates function invocation with different values

```javascript
function addNumbers(a, b) {
    return a + b;
}
let result = addNumbers(105, 25);
console.log("Result:", result);
```
**Output:**
```
Result: 130
```
**Requirement:** 
- Node.js installed on your system
- or IDE

**Run:**
```bash
node addition.js
node funAddition.js
```
---
Author: `heysanzu`
