# Understanding var, let, and const in JavaScript

In JavaScript, variables are used to store data. The way we declare variables has evolved over time, and today, JavaScript offers three ways to declare them: var, let, and const.


## 1. var (The Old Way)

var was the original way to declare variables in JavaScript. However, it has some quirks that make it less ideal in modern code.

### Key Characteristics of var:

#### Function Scoped:

Variables declared with var are only accessible within the function where they are defined.
They are not block-scoped, meaning they ignore {} blocks (like in loops or conditionals).

#### Can Be Redeclared:

You can declare the same variable multiple times without any errors.

#### Hoisting:

Variables declared with var are "hoisted" to the top of their scope, meaning they can be used even before their declaration.

#### Why Avoid var?

The lack of block scope can lead to bugs, especially in large programs. Modern JavaScript prefers let and const.

## 2. let (Modern and Recommended)

let is a newer way to declare variables, introduced in ES6. It fixes many issues of var.

### Key Characteristics of let:

#### Block Scoped:

Variables declared with let are only accessible within the block ({}) where they are defined.

#### Cannot Be Redeclared:

You cannot declare the same variable twice within the same scope.

#### Hoisting (but safer):

While let is hoisted, it is not initialized until the code execution reaches its declaration. This prevents using it before declaration.

#### Why Use let?

let is suitable for variables whose values might change later. Its block scope makes it safer to use in modern code.
