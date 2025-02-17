# **Table-Based Navigation and HTML Collection in JavaScript** 

In this lecture, we explore how to navigate tables in the DOM using JavaScript and how to work with **HTML collections**.  

---

## **1. Table-Based Navigation in JavaScript**
Tables in HTML consist of structured rows (`<tr>`) and cells (`<td>`). JavaScript provides special methods to navigate within tables efficiently.

### **Table Example:**
```html
<table id="myTable" border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>25</td>
    </tr>
    <tr>
        <td>Bob</td>
        <td>30</td>
    </tr>
</table>
```

### **Accessing the Table and Its Elements in JavaScript**
```javascript
let table = document.getElementById("myTable");
console.log(table.rows); // Returns all table rows
console.log(table.rows[1].cells); // Returns all cells of the second row
console.log(table.rows[1].cells[0].innerText); // Outputs: Alice
```

---

## **2. Special Table Properties in JavaScript**
| Property | Description |
|----------|-------------|
| `table.rows` | Returns all `<tr>` elements |
| `table.caption` | Returns `<caption>` element, if available |
| `table.tHead` | Returns `<thead>` element, if available |
| `table.tBodies` | Returns a collection of `<tbody>` elements |
| `table.tFoot` | Returns `<tfoot>` element, if available |

### **Example:**
```javascript
console.log(table.tBodies[0]); // Access the first `<tbody>`
```

---

## **3. Adding Special Features to Tables**
We can dynamically manipulate tables using JavaScript, such as adding or removing rows.

### **Adding a New Row Dynamically:**
```javascript
let newRow = table.insertRow();
let newCell1 = newRow.insertCell(0);
let newCell2 = newRow.insertCell(1);
newCell1.innerText = "Charlie";
newCell2.innerText = "28";
```

### **Deleting a Row Dynamically:**
```javascript
table.deleteRow(1); // Deletes the second row
```

---

## **4. HTMLCollection in JavaScript**
An **HTMLCollection** is a live collection of HTML elements that updates when elements are added or removed.

### **Example:**
```javascript
let rows = document.getElementsByTagName("tr");
console.log(rows); // Returns an HTMLCollection of all table rows
```

| Feature | `HTMLCollection` | `NodeList` |
|---------|-----------------|------------|
| Live updates? | ✅ Yes | ❌ No |
| Access by index? | ✅ Yes | ✅ Yes |
| Methods available | Limited | More (like `forEach()`) |

### **Converting an HTMLCollection to an Array**
```javascript
let rowsArray = Array.from(rows);
rowsArray.forEach(row => console.log(row.innerText));
```

---

## **5. Summary of Table-Based Navigation**
| Feature | Method |
|---------|--------|
| Get all rows | `table.rows` |
| Get all cells in a row | `table.rows[index].cells` |
| Add a new row | `table.insertRow()` |
| Remove a row | `table.deleteRow(index)` |
| Access first `<tbody>` | `table.tBodies[0]` |

---

## **6. Conclusion**
Using JavaScript, we can efficiently navigate and manipulate HTML tables. Understanding **HTMLCollection** helps in dynamically updating table structures without reloading the page. 🚀


