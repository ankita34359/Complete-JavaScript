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

## The do-while Loop

### What is a do-while Loop?

The do-while loop is similar to the while loop, except the condition is checked after the code block is executed. This means the code inside the do block will run at least once, even if the condition is false.

### Syntax:

```javascript

do {
  // Code to execute at least once
} while (condition);

```

### How It Works:

- The code inside the do block runs first.
- The condition is then checked.
- If the condition is true, the loop continues. If false, the loop stops.
