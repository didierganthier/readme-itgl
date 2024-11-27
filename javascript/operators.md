# Lesson Plan: JavaScript Operators

## Objective:
Students will learn about JavaScript operators, including arithmetic, comparison, logical, and assignment operators. By the end of the lesson, they should be able to use operators to perform calculations, make decisions, and manipulate values.

---

## 1. **Introduction to Operators**

**Definition:**
An operator is a symbol or keyword used to perform operations on values or variables. For example, `+` is used to add two numbers.

**Types of Operators:**
1. Arithmetic Operators
2. Comparison Operators
3. Logical Operators
4. Assignment Operators

---

## 2. **Arithmetic Operators**

**Explanation:** Arithmetic operators are used for mathematical operations.

| Operator | Description       | Example          | Output   |
|----------|-------------------|------------------|----------|
| `+`      | Addition          | `5 + 3`          | `8`      |
| `-`      | Subtraction       | `10 - 6`         | `4`      |
| `*`      | Multiplication    | `2 * 4`          | `8`      |
| `/`      | Division          | `12 / 3`         | `4`      |
| `%`      | Modulus (Remainder) | `10 % 3`       | `1`      |
| `**`     | Exponentiation    | `2 ** 3`         | `8`      |

**Activity:**
Write a program to calculate the sum, difference, product, and quotient of two numbers. Log the results in the console.

```javascript
let a = 15;
let b = 4;

console.log('Sum:', a + b);
console.log('Difference:', a - b);
console.log('Product:', a * b);
console.log('Quotient:', a / b);
console.log('Remainder:', a % b);
```

---

## 3. **Comparison Operators**

**Explanation:** These operators compare two values and return `true` or `false`.

| Operator | Description             | Example       | Output   |
|----------|-------------------------|---------------|----------|
| `===`    | Strict equality         | `5 === 5`     | `true`   |
| `!==`    | Strict inequality       | `5 !== 4`     | `true`   |
| `>`      | Greater than            | `10 > 5`      | `true`   |
| `<`      | Less than               | `5 < 10`      | `true`   |
| `>=`     | Greater than or equal to| `5 >= 5`      | `true`   |
| `<=`     | Less than or equal to   | `4 <= 6`      | `true`   |

**Activity:**
Write a program that compares two numbers and prints whether the first number is greater, equal, or less than the second number.

```javascript
let x = 7;
let y = 10;

if (x > y) {
    console.log('x is greater than y');
} else if (x < y) {
    console.log('x is less than y');
} else {
    console.log('x is equal to y');
}
```

---

## 4. **Logical Operators**

**Explanation:** Logical operators are used to combine multiple conditions.

| Operator | Description                  | Example            | Output |
|----------|------------------------------|--------------------|--------|
| `&&`     | Logical AND (both true)      | `true && false`    | `false`|
| `||`     | Logical OR (at least one true)| `true || false`   | `true` |
| `!`      | Logical NOT (invert boolean) | `!true`            | `false`|

**Activity:**
Write a program that checks if a number is between 5 and 10 (inclusive).

```javascript
let num = 8;

if (num >= 5 && num <= 10) {
    console.log('The number is between 5 and 10.');
} else {
    console.log('The number is outside the range.');
}
```

---

## 5. **Assignment Operators**

**Explanation:** These operators assign values to variables.

| Operator | Description    | Example   | Equivalent To |
|----------|----------------|-----------|---------------|
| `=`      | Assignment     | `x = 5`   | `x = 5`       |
| `+=`     | Add and assign | `x += 3`  | `x = x + 3`   |
| `-=`     | Subtract and assign | `x -= 2` | `x = x - 2` |
| `*=`     | Multiply and assign | `x *= 4` | `x = x * 4` |
| `/=`     | Divide and assign   | `x /= 2` | `x = x / 2` |
| `%=`     | Modulus and assign  | `x %= 3` | `x = x % 3` |

**Activity:**
Demonstrate the use of `+=`, `-=`, and other assignment operators.

```javascript
let z = 10;

z += 5;
console.log('After +=:', z); // 15

z -= 3;
console.log('After -=:', z); // 12

z *= 2;
console.log('After *=:', z); // 24

z /= 4;
console.log('After /=:', z); // 6

z %= 2;
console.log('After %=:', z); // 0
```

---

## 6. **Interactive Group Project**

**Objective:** Create a basic calculator that performs addition, subtraction, multiplication, and division based on user input.

**Steps:**
1. Prompt the user to enter two numbers.
2. Prompt the user to select an operation (`+`, `-`, `*`, `/`).
3. Perform the selected operation and display the result.

**Code Example:**

```javascript
let num1 = parseFloat(prompt('Enter the first number:'));
let num2 = parseFloat(prompt('Enter the second number:'));
let operation = prompt('Enter an operation (+, -, *, /):');

let result;

if (operation === '+') {
    result = num1 + num2;
} else if (operation === '-') {
    result = num1 - num2;
} else if (operation === '*') {
    result = num1 * num2;
} else if (operation === '/') {
    result = num1 / num2;
} else {
    result = 'Invalid operation';
}

console.log('Result:', result);
```

---

## Conclusion
- Review each type of operator with examples.
- Discuss how operators can be combined for more complex logic.
- Encourage students to explore operators further in their homework and projects.

