# Conditional Statements in JavaScript

Conditional statements are used in JavaScript to make decisions in our code. They allow us to execute certain blocks of code based on specific conditions.

## 1. What Are Conditional Statements?

Conditional statements are programming constructs that execute a block of code only if a specified condition evaluates to true. These are essential for implementing logic in programs.

## 2. Types of Conditional Statements in JavaScript

### a. if Statement

The if statement checks a condition and executes the code block if the condition is true.

Syntax:

```javascript

if (condition) {
  // Code to execute if condition is true
}

```
### b. if...else Statement

The if...else statement provides an alternative block of code to execute when the condition is false.

Syntax:

```javascript
if (condition) {
  // Code to execute if condition is true
} else {
  // Code to execute if condition is false
}
```

### c. if...else if...else Statement

This statement is used to test multiple conditions. It checks conditions in sequence and executes the block of the first true condition.

Syntax:

```javascript
if (condition1) {
  // Code to execute if condition1 is true
} else if (condition2) {
  // Code to execute if condition2 is true
} else {
  // Code to execute if none of the conditions are true
}
```

### d. switch Statement

The switch statement evaluates an expression and matches its value against multiple case clauses. It is used when you need to compare a single value against several possibilities.

Syntax:

```javascript
switch (expression) {
  case value1:
    // Code to execute if expression === value1
    break;
  case value2:
    // Code to execute if expression === value2
    break;
  default:
    // Code to execute if no case matches
}
```

### e. Ternary Operator (condition ? expr1 : expr2)

The ternary operator is a shorthand way to write if...else statements. It evaluates a condition and returns one of two values.

Syntax:

```javascript
condition ? expressionIfTrue : expressionIfFalse;

```

### f. Nested Conditionals

Conditionals can be nested within one another to handle more complex decision-making.
