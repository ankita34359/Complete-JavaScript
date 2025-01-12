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

### Key Difference Between while and do-while

- The while loop checks the condition first and may not execute the code block if the condition is false.
- The do-while loop guarantees that the code block will execute at least once, even if the condition is false.

## Use Cases

### When to Use while

When you don’t know how many times the loop will run but want to stop when a condition becomes false.

### When to Use do-while

When you need the loop to execute at least once before checking the condition.

## Differences Between `while` and `do-while`

The table below summarizes the differences between `while` and `do-while` loops in JavaScript:

| **Feature**              | **while**                           | **do-while**                        |
|--------------------------|--------------------------------------|--------------------------------------|
| **Condition Check**      | Before the code block executes      | After the code block executes        |
| **Executes At Least Once**| No                                  | Yes                                  |
| **Use Case**             | When you want to repeat until a condition becomes false | When the code must run at least once |


## Conclusion

- `while Loop:` Best when the number of iterations depends on a condition.
- `do-while Loop:` Use when the code must run at least once, regardless of the condition.
- Always ensure your loops have an exit condition to prevent infinite loops.
- Use break and continue wisely to control loop flow.
