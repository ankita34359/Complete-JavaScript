# While and Do-While Loops in JavaScript

`while` and `do-while` loops allow us to repeatedly execute a block of code based on a condition. They are particularly useful when the number of iterations is not known beforehand.

## The while Loop

### What is a while Loop?

The while loop executes a block of code as long as a specified condition is true.

### Syntax:

```javascript

while (condition) {
  // Code to execute as long as the condition is true
}

```

### How It Works

- The condition is evaluated before each iteration.
- If the condition evaluates to true, the code block runs.
- The loop stops when the condition becomes false.

### Infinite Loops

Be cautious! If the condition never becomes false, the loop will run forever.
