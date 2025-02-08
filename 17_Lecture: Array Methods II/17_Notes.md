# Advanced Array Methods in JavaScript

In this part, we will explore more array methods that help in manipulating and modifying arrays effectively.

## 1. concat() - Merge Multiple Arrays

The concat() method merges two or more arrays without modifying the original arrays.

### Key Points:

- Does not modify the original arrays.
- Can merge multiple arrays at once.

## 2. sort() - Sort an Array

The sort() method sorts an array in ascending order by default.

**Example:** 

```javascript
let numbers = [40, 100, 1, 5, 25, 10];
numbers.sort();
console.log(numbers); // Output: [1, 10, 100, 25, 40, 5]
```

**Problem:** It sorts elements as strings, so 100 comes before 25.

To fix this, use a comparison function:

```javascript
numbers.sort((a, b) => a - b);
console.log(numbers); // Output: [1, 5, 10, 25, 40, 100]
```

