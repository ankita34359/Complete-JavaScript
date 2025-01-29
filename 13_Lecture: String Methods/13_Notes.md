# String Methods in JavaScript

Strings in JavaScript come with built-in methods that allow us to manipulate, search, and analyze text efficiently. This lecture covers commonly used string methods with clear explanations and examples.

---

### 1. length  

The length property returns the number of characters in a string.

### 2. toUpperCase() and toLowerCase()

These methods convert a string to uppercase or lowercase.

### 3. trim()

Removes whitespace from both ends of a string.

### 4. slice(start, end)

Extracts a part of a string and returns it as a new string. The `start` index is inclusive, and the `end` index is exclusive.

### 5. substring(start, end)

Similar to `slice()`, but it doesn’t accept negative indexes.


### 6. replace(searchValue, newValue)

Replaces the first occurrence of a specified substring with another string.


### 7. replaceAll(searchValue, newValue)

Replaces all occurrences of a specified substring.

### 8. concat()

Joins two or more strings together.

 
### 9. includes(substring)

Checks if a string contains a specified substring. Returns true or false.

### 10. startsWith(substring) and endsWith(substring)

- `startsWith()` checks if a string starts with a specified substring.
- `endsWith()` checks if a string ends with a specified substring.

### 11. split(delimiter)

Splits a string into an array of substrings based on a specified delimiter.


## 12. indexOf(substring) and lastIndexOf(substring)

- `indexOf()` returns the index of the first occurrence of a substring.
- `lastIndexOf()` returns the index of the last occurrence.

### 13. charAt(index)

Returns the character at a specified index.

## 14. charCodeAt(index)

Returns the Unicode value of the character at a specified index.

### 15. repeat(count)

Repeats a string a specified number of times.


### 16. padStart(targetLength, padString) and padEnd(targetLength, padString)

- `padStart()` pads a string at the beginning until it reaches the target length.
- `padEnd()` pads a string at the end.

### 17. toString()

Converts a value to a string. 

---

# String Methods Summary

The table below provides an overview of commonly used JavaScript string methods, their descriptions, and examples:


| **Method**       | **Description**                                | **Example**                           |
|-------------------|-----------------------------------------------|---------------------------------------|
| **length**        | Returns string length                        | `"Hello".length → 5`                  |
| **toUpperCase()** | Converts to uppercase                        | `"hello".toUpperCase() → "HELLO"`     |
| **toLowerCase()** | Converts to lowercase                        | `"HELLO".toLowerCase() → "hello"`     |
| **trim()**        | Removes whitespace                           | `" hi ".trim() → "hi"`                |
| **slice()**       | Extracts part of a string                    | `"Hello".slice(1, 4) → "ell"`         |
| **replace()**     | Replaces the first match                     | `"abc".replace("a", "x") → "xbc"`     |
| **replaceAll()**  | Replaces all matches                         | `"aaa".replaceAll("a", "x") → "xxx"`  |
| **includes()**    | Checks if string contains a substring        | `"abc".includes("b") → true`          |
| **split()**       | Splits string into an array                  | `"a,b".split(",") → ["a", "b"]`       |
| **indexOf()**     | First occurrence index                       | `"abcabc".indexOf("b") → 1`           |
| **startsWith()**  | Checks if string starts with a substring      | `"abc".startsWith("a") → true`        |
| **charAt()**      | Gets character at index                      | `"abc".charAt(1) → "b"`               |
| **repeat()**      | Repeats string                               | `"ha".repeat(3) → "hahaha"`           |
