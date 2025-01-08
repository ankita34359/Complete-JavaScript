# Expressions and Operators in JavaScript

In JavaScript, expressions and operators are fundamental building blocks that let us to perform actions, calculations, and logic in our code.

## 1. Expressions

### What is an Expression?

An expression is any valid unit of code that resolves to a value.

### Types of Expressions:

- **Arithmetic Expressions:** Perform mathematical operations.

- **String Expressions:** Combine or manipulate strings.

- **Logical Expressions:** Evaluate to true or false.

- **Function Expressions:** Define a function as part of an expression.

- **Conditional Expressions:** Return different values based on a condition (ternary operator).

## 2. Operators

### What is an Operator?

An operator is a symbol or keyword that performs an operation on operands.

### Types of Operators:

-  Arithmetic Operators

Used for mathematical calculations.

| **Operator** | **Description**          | **Example** | **Result** |
|--------------|--------------------------|-------------|------------|
| `+`          | Addition                 | `5 + 3`     | `8`        |
| `-`          | Subtraction              | `5 - 3`     | `2`        |
| `*`          | Multiplication           | `5 * 3`     | `15`       |
| `/`          | Division                 | `6 / 3`     | `2`        |
| `%`          | Modulus (remainder)      | `5 % 2`     | `1`        |
| `**`         | Exponentiation           | `2 ** 3`    | `8`        |

2. Assignment Operators
   
Used to assign values to variables.

| **Operator** |   **Description**       | **Example**                          |
|--------------|-------------------------|--------------------------------------|
| `=`          | Assign                  | `x = 10`                             |
| `+=`         | Add and assign          | `x += 5` (equivalent to `x = x + 5`) |
| `-=`         | Subtract and assign     | `x -= 2` (equivalent to `x = x - 2`) |
| `*=`         | Multiply and assign     | `x *= 3` (equivalent to `x = x * 3`) |
| `/=`         | Divide and assign       | `x /= 2` (equivalent to `x = x / 2`) |
| `%=`         | Modulus and assign      | `x %= 3` (equivalent to `x = x % 3`) |

3. Comparison Operators
   
Used to compare two values. They return a Boolean (true or false).

| **Operator** | **Description**         | **Example**    | **Result** |
|--------------|-------------------------|----------------|------------|
| `==`         | Equal to                | `5 == "5"`     | `true`     |
| `===`        | Strict equal to         | `5 === "5"`    | `false`    |
| `!=`         | Not equal to            | `5 != "5"`     | `false`    |
| `!==`        | Strict not equal to     | `5 !== "5"`    | `true`     |
| `>`          | Greater than            | `5 > 3`        | `true`     |
| `<`          | Less than               | `5 < 3`        | `false`    |
| `>=`         | Greater than or equal   | `5 >= 5`       | `true`     |
| `<=`         | Less than or equal      | `5 <= 4`       | `false`    |

4. Logical Operators
   
Used to combine multiple conditions.

| **Operator** | **Description** | **Example**      | **Result** |
|--------------|-----------------|------------------|------------|
| `&&`         | Logical AND     | `true && false`  | `false`    |
| `||`         | Logical OR      | `true || false`  | `true`     |
| `!`          | Logical NOT     | `!true`          | `false`    |

5. Bitwise Operators
   
Perform operations at the binary level.

| **Operator** | **Description** | **Example**           |
|--------------|-----------------|---------------------- |
| `&`          | AND             | `5 & 1` (0101 & 0001) |
| `|`          | OR              | `5 | 1` (0101 | 0001) |
| `^`          | XOR             | `5 ^ 1` (0101 ^ 0001) |
| `~`          | NOT             | `~5`                  |
| `<<`         | Left shift      | `5 << 1`              |
| `>>`         | Right shift     | `5 >> 1`              |

6. Special Operators
   
Ternary Operator (condition ? true : false):

Typeof Operator:

Delete Operator (removes properties from objects):

Spread and Rest Operators (...):

