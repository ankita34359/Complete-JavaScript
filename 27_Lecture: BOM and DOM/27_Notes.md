# **Window Object, BOM, DOM, and Changing Styles in JavaScript**

JavaScript provides powerful ways to interact with the browser through the **Window Object**, **Browser Object Model (BOM)**, and **Document Object Model (DOM)**. These allow developers to manipulate browser settings, interact with webpage elements, and dynamically change styles.

---

## **1. Window Object in JavaScript**
The `window` object is the global object representing the browser window. It provides properties and methods to control browser functions.

### **Common Window Object Methods:**
| Method | Description |
|--------|-------------|
| `window.alert("Hello!")` | Displays an alert box |
| `window.confirm("Are you sure?")` | Displays a confirmation box |
| `window.prompt("Enter your name:")` | Displays an input prompt |
| `window.open("https://example.com")` | Opens a new browser window |
| `window.close()` | Closes the current browser window |

---

## **2. Browser Object Model (BOM)**
The **BOM** allows JavaScript to interact with the browser apart from the webpage content. It includes objects like `navigator`, `screen`, `location`, and `history`.

### **Common BOM Properties and Methods:**
| Property/Method | Description |
|---------------|-------------|
| `navigator.userAgent` | Returns browser details |
| `location.href` | Returns or sets the URL |
| `history.back()` | Goes back in browser history |
| `screen.width` | Gets screen width |
| `screen.height` | Gets screen height |

Example:
```javascript
console.log("Browser Name: ", navigator.userAgent);
console.log("Current URL: ", location.href);
```

---

## **3. Document Object Model (DOM)**
The **DOM** represents the structure of an HTML document. JavaScript can be used to modify elements dynamically.

### **Common DOM Methods:**
| Method | Description |
|--------|-------------|
| `document.getElementById("myId")` | Selects an element by ID |
| `document.querySelector(".myClass")` | Selects the first matching element |
| `document.createElement("div")` | Creates a new HTML element |
| `document.body.appendChild(newElement)` | Adds an element to the page |

Example:
```javascript
let heading = document.getElementById("title");
heading.innerText = "Hello, JavaScript!";
```

---

## **4. Changing Styles with JavaScript**
JavaScript allows dynamic changes to the webpage's style using the `document` object.

### **Changing Styles Dynamically**
Example:
```javascript
let para = document.getElementById("myPara");
para.style.color = "blue";
para.style.fontSize = "20px";
```

### **Adding and Removing CSS Classes**
Example:
```javascript
let box = document.querySelector(".box");
box.classList.add("highlight");
```

---

## **5. Practical Use Cases**

| Use Case | JavaScript Feature |
|----------|-------------------|
| Show alerts or confirmations | `window.alert()`, `window.confirm()` |
| Get browser details | `navigator.userAgent` |
| Modify webpage content | `document.getElementById()`, `innerText` |
| Change styles dynamically | `element.style.property` |

---

## **Conclusion**
Understanding the **Window Object**, **BOM**, and **DOM** allows developers to create dynamic, interactive, and responsive web applications. Mastering these concepts enables effective manipulation of both the browser environment and the webpage content. 🚀
