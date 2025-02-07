# Understanding Arrays in JavaScript

## What is an Array?
An array in JavaScript is a special variable used to store multiple values in a single variable. It allows efficient data storage and manipulation. Arrays can hold different data types, including numbers, strings, and even objects.

---

## How to Access Values from an Array

In JavaScript, arrays are zero-indexed, meaning the first element starts at index 0.

```javascript
let numbers = [10, 20, 30, 40, 50];
console.log(numbers[0]); // Output: 10
console.log(numbers[2]); // Output: 30
console.log(numbers[4]); // Output: 50
```

If we try to access an index that does not exist, JavaScript returns undefined:

---

## How to Add a New Value to an Array

### 1. Adding a New Value Without Using Array Methods
   
**Using the Index Directly**

We can add a new value to an array by assigning a value to an index that doesn’t exist yet.

```javascript
let numbers = [10, 20, 30];
numbers[3] = 40; // Adding value at index 3
console.log(numbers); // Output: [10, 20, 30, 40]
```

If you assign a value at an index greater than the current length, JavaScript fills the missing indexes with undefined.

```javascript
let numbers = [10, 20, 30];
numbers[5] = 50; 
console.log(numbers); // Output: [10, 20, 30, undefined, undefined, 50]
```

**Using the length Property**

We can use the .length property to add a value at the end of an array.

```javascript
let colors = ["Red", "Blue"];
colors[colors.length] = "Green"; // Adds "Green" at index 2
console.log(colors); // Output: ["Red", "Blue", "Green"]
```

---

## How to Change a Value in an Array

You can change an array element by directly accessing its index and assigning a new value.

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
fruits[1] = "Mango"; // Changing "Banana" to "Mango"
console.log(fruits); // Output: ["Apple", "Mango", "Cherry"]
```

If you try to update an index that doesn’t exist, JavaScript will create a new element at that index.

```javascript
let numbers = [1, 2, 3];
numbers[5] = 10; 
console.log(numbers); // Output: [1, 2, 3, undefined, undefined, 10]
```

---

## Note

Strings are immutable means they cannot change.

Array are mutable means they can change.

---

## Conclusion

- You can add values by assigning them to an empty index or using .length.
- You can change values by assigning a new value to an existing index.
- Be cautious when adding values at higher indexes, as it creates undefined gaps in the array.
