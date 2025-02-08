# Understanding Array Methods in JavaScript

In this lecture, we will explore some essential array methods in JavaScript that help in manipulating arrays effectively.

## 1.) toString() - Convert an Array to a String

The `toString()` method converts an array into a comma-separated string.

### Key Points:

- It does not modify the original array.
- Only converts elements to a string representation.
- No custom separators (use join() for that).

## 2.) join() - Convert an Array to a String with a Custom Separator

The join() method is similar to toString(), but allows you to specify a separator.

### Key Points:

- You can define any separator (,, -, |, etc.).
- It does not modify the original array.

## 3. pop() - Remove the Last Element from an Array

The pop() method removes the last element from an array and returns it.

### Key Points:

- Modifies the original array.
- Returns the removed element.


## 4. push() - Add an Element to the End of an Array

The push() method adds one or more elements to the end of an array.

### Key Points:

- Modifies the original array.
- Returns the new length of the array.

## 5. shift() - Remove the First Element from an Array

The shift() method removes the first element and returns it.

### Key Points:

- Modifies the original array.
- Returns the removed element.


## 6. unshift() - Add Elements to the Beginning of an Array

The unshift() method adds one or more elements to the beginning of an array.

### Key Points:

- Modifies the original array.
- Returns the new length of the array.

  
## 7. delete - Remove an Element but Keep the Index

The delete keyword removes an element from an array without shifting the remaining elements.

### Key Points:

- It removes the element but leaves an empty space (undefined).
- The array length does not change.

**Warning:** It’s generally not recommended to use delete for arrays because it leaves gaps. Use splice() instead if you want to remove an element completely.
