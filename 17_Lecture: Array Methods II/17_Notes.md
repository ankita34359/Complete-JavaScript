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

### Key Points:

- Changes the original array.
- Sorts alphabetically by default.
- Use a custom comparison function for numerical sorting.

## 3. splice() - Add/Remove Elements from an Array

The splice() method is used to add, remove, or replace elements in an array.

**Removing Elements:**

```javascript
let colors = ["Red", "Green", "Blue", "Yellow"];
colors.splice(1, 2);  // Removes 2 elements starting from index 1
console.log(colors);   // Output: ["Red", "Yellow"]
```

**Adding Elements:**

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
fruits.splice(1, 0, "Mango", "Orange"); // Adds at index 1
console.log(fruits);  // Output: ["Apple", "Mango", "Orange", "Banana", "Cherry"]
```

**Replacing Elements:**

```javascript
let numbers = [10, 20, 30, 40];
numbers.splice(1, 2, 100, 200); // Replaces 2 elements at index 1
console.log(numbers); // Output: [10, 100, 200, 40]
```

### Key Points:

- Modifies the original array.
- Can be used to add, remove, or replace elements.

## 4. slice() - Extract a Portion of an Array

The slice() method extracts a portion of an array without modifying the original array.

**Syntax:**

```js
array.slice(startIndex, endIndex);
```

**Note** The endIndex is not included in the extracted part.

### Key Points:

- Does not modify the original array.
- Can be used to copy parts of an array.

## 5. reverse() - Reverse the Order of an Array

The reverse() method reverses the order of elements in an array.

### Key Points:

- Modifies the original array.
- Useful for reversing sorted arrays.

##  Array Methods Summary

The table below provides an overview of commonly used JavaScript array methods, whether they modify the original array, and what they return:

| **Method**    | **Description**            | **Modifies Original Array?** | **Returns**             |
|--------------|----------------------------|----------------------------|--------------------------|
| **concat()**  | Merges arrays               | ❌ No                      | New merged array         |
| **sort()**    | Sorts elements              | ✅ Yes                     | Sorted array             |
| **splice()**  | Adds/removes elements       | ✅ Yes                     | Removed elements         |
| **slice()**   | Extracts elements           | ❌ No                      | Extracted elements       |
| **reverse()** | Reverses array order        | ✅ Yes                     | Reversed array          |
