# JavaScript Exercises README

## Overview
This document provides the solution to five JavaScript exercises, including their code implementation and explanations.

---

## Q1: Evaluate the Expressions
The following expressions demonstrate basic JavaScript operations:

```javascript
console.log(-5 * 3); // -15
console.log("JavaScript" + 50); // JavaScript50
console.log(17 % 5); // 2
console.log(5 % 17); // 5
console.log(5 / 10); // 0.5
console.log(4 === '4'); // false
console.log(4 != 5); // true
console.log(7 <= 8); // true
console.log("Hello" + 5); // Hello5

let x = 9.7;
console.log(Math.ceil(x) - Math.floor(x)); // 1
console.log(Math.pow(x, 2)); // 94.0899999
```

---

## Q2: Read a Number
This program reads a number from the user and displays it:

```javascript
let y = prompt("Enter Your Number plz : ");
alert("your Number is :" + y);
```

### Steps:
1. Use `prompt()` to read user input.
2. Display the number using `alert()`.

---

## Q3: Sum of Two Numbers
This program calculates the sum of two user-provided numbers:

```javascript
let num1 = prompt("Enter your num 1 :");
let num2 = prompt("Enter your num 2 :");
let sum = Number(num1) + Number(num2);
alert("your result:" + sum);
```

### Steps:
1. Use `prompt()` to read two numbers.
2. Convert inputs to numbers using `Number()`.
3. Calculate the sum and display the result using `alert()`.

---

## Q4: Product of Two Numbers
This program calculates the product of two user-provided numbers:

```javascript
let numP1 = prompt("Enter your num 1 :");
let numP2 = prompt("Enter your num 2 :");
let Product = numP1 * numP2;
alert("your result:" + Product);
```

### Steps:
1. Use `prompt()` to read two numbers.
2. Multiply the numbers directly.
3. Display the product using `alert()`.

---

## Q5: Division of Two Numbers
This program calculates the division of two user-provided numbers and also calculates their sum:

```javascript
let numD1 = prompt("Enter your num 1 :");
let numD2 = prompt("Enter your num 2 :");
let dividing = numD1 / numD2;
let sum2 = Number(numD1) + Number(numD2);
alert("your result:" + dividing);
alert("your result:" + sum2);
```

### Steps:
1. Use `prompt()` to read two numbers.
2. Calculate the division result and the sum.
3. Display both results using `alert()`.

---

## Notes
- Ensure to handle invalid inputs in real-world applications.
- Add additional error handling for operations like division by zero if needed.

