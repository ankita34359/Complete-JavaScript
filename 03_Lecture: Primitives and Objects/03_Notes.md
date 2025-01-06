# Primitives and Objects in JavaScript

## 1. Primitives

Primitives are the most basic building blocks of JavaScript. They represent single, immutable values.

### Types of Primitives

JavaScript has the following primitive data types:

- **Number:** Represents numeric values, including integers and floating-point numbers.

    Special numeric values:

     - Infinity (e.g., 1 / 0)

     - -Infinity

     - NaN (Not a Number, e.g., 0 / 0).

- **String:** Represents text enclosed in single ('), double ("), or backticks (` for template literals).

- **Boolean:** Represents logical values: true or false.

- **Null:** Represents the intentional absence of any object value. It is a placeholder for "nothing."

- **Undefined:** Represents a variable that has been declared but not assigned a value.

- **Symbol:** Represents unique values introduced in ES6.

- **BigInt:** Represents very large integers introduced in ES11 (2020).

### Characteristics of Primitives:

- **Immutable:** The value cannot be changed after it’s created.

- **Stored by Value:** When you copy a primitive value, a new copy is created.

## 2. Objects
   
Objects are complex data structures that can store multiple values and methods. They can hold key-value pairs, functions, and even other objects.

### Key Characteristics of Objects:

- **Mutable:** Their values can be changed.

- **Stored by Reference:** When you copy an object, only the reference to the object is copied, not the object itself.
