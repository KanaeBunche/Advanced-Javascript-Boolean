Understood! Here’s the lesson plan for teaching boolean values in JavaScript without showing the exercises:

---

# Lesson: Boolean Values in JavaScript

## Overview

Booleans are a fundamental data type in JavaScript that represent two values: `true` and `false`. They are commonly used in conditional statements to control the flow of a program based on certain conditions.

### Objectives

- Understand what boolean values are.
- Learn how to use booleans in conditional statements.
- Practice writing and using boolean expressions.

## What is a Boolean?

A **boolean** represents one of two values: `true` or `false`.

```javascript
let isJavaScriptFun = true;
let isThisLessonBoring = false;
```

### Boolean Expressions

Boolean expressions evaluate to `true` or `false`. They are often used in conditional statements to determine which code block should be executed.

```javascript
let a = 5;
let b = 10;
let isEqual = (a === b); // false
```

### Common Boolean Operations

1. **Equality (`==`) and Strict Equality (`===`)**
    - `==` checks for equality with type coercion.
    - `===` checks for equality without type coercion.

    ```javascript
    console.log(5 == "5");  // true
    console.log(5 === "5"); // false
    ```

2. **Inequality (`!=`) and Strict Inequality (`!==`)**
    - `!=` checks for inequality with type coercion.
    - `!==` checks for inequality without type coercion.

    ```javascript
    console.log(5 != "5");  // false
    console.log(5 !== "5"); // true
    ```

3. **Greater Than (`>`) and Less Than (`<`)**
    - `>` checks if the left operand is greater than the right operand.
    - `<` checks if the left operand is less than the right operand.

    ```javascript
    console.log(10 > 5);   // true
    console.log(10 < 5);   // false
    ```

4. **Greater Than or Equal To (`>=`) and Less Than or Equal To (`<=`)**
    - `>=` checks if the left operand is greater than or equal to the right operand.
    - `<=` checks if the left operand is less than or equal to the right operand.

    ```javascript
    console.log(10 >= 5);  // true
    console.log(10 <= 5);  // false
    ```

## Using Booleans in Conditional Statements

Conditional statements execute different blocks of code based on boolean expressions.

```javascript
let age = 18;

if (age >= 18) {
    console.log("You are eligible to vote.");
} else {
    console.log("You are not eligible to vote yet.");
}
```

### Explanation:
- The condition `age >= 18` evaluates to `true`, so the message "You are eligible to vote." is printed.

## Summary

- Booleans represent `true` or `false`.
- Boolean expressions evaluate to `true` or `false`.
- Booleans are commonly used in conditional statements to control the flow of a program.


