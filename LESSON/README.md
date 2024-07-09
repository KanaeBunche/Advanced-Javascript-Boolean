Here's a structured lesson plan for teaching comparison operators in JavaScript:

---

# Lesson: Comparison Operators in JavaScript

## Overview

Comparison operators in JavaScript are used to compare two values and return a boolean result (`true` or `false`). They are essential for making decisions and controlling the flow of your programs based on conditions.

### Objectives

- Understand the syntax and purpose of comparison operators.
- Learn about different types of comparison operators in JavaScript.
- Practice using comparison operators with practical examples.

## Types of Comparison Operators

### Equality Operators

- **Equal (`==`)**: Checks if two values are equal, but performs type coercion if necessary.
- **Strict Equal (`===`)**: Checks if two values are equal without type coercion.

```javascript
console.log(5 == "5");    // true
console.log(5 === "5");   // false
```

### Inequality Operators

- **Not Equal (`!=`)**: Checks if two values are not equal, performing type coercion.
- **Strict Not Equal (`!==`)**: Checks if two values are not equal without type coercion.

```javascript
console.log(5 != "5");    // false
console.log(5 !== "5");   // true
```

### Relational Operators

- **Greater Than (`>`)**: Checks if the left operand is greater than the right operand.
- **Greater Than or Equal To (`>=`)**: Checks if the left operand is greater than or equal to the right operand.
- **Less Than (`<`)**: Checks if the left operand is less than the right operand.
- **Less Than or Equal To (`<=`)**: Checks if the left operand is less than or equal to the right operand.

```javascript
console.log(10 > 5);     // true
console.log(10 >= 10);   // true
console.log(10 < 5);     // false
console.log(10 <= 10);   // true
```

## Example: Using Comparison Operators

```javascript
let x = 10;
let y = 5;

console.log(x > y);      // true
console.log(x === y);    // false
console.log(x !== y);    // true
```

### Explanation:
- **Comparison**: Each statement evaluates whether the condition (`x > y`, `x === y`, `x !== y`) is true or false based on the values of `x` and `y`.

## Example: Conditional Statements

Comparison operators are commonly used in conditional statements (`if`, `else`, `else if`) to control the flow of execution based on different conditions.

```javascript
let age = 18;

if (age >= 18) {
    console.log("You are eligible to vote.");
} else {
    console.log("You are not eligible to vote yet.");
}
```

### Explanation:
- **Condition**: `age >= 18` checks if the variable `age` is 18 or older.
- **Conditional Statement**: Executes different blocks of code based on whether the condition is true or false.

### Output:
```
You are eligible to vote.
```

## Summary

- Comparison operators in JavaScript allow you to compare two values and determine their relationship.
- They are crucial for making decisions and controlling program flow based on conditions.
- Practice using comparison operators in various scenarios to enhance your programming skills.

---

This lesson plan introduces comparison operators in JavaScript with clear explanations and practical examples. Adjust and expand as needed to suit your teaching style and the level of your students.