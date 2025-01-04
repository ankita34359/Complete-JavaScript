## Simple Examples Of Statically Typed Language and  Dynamically Typed Language: 

### Statically Typed Language Example (C):

```c
#include <stdio.h>

int main() {

    // Declaring a variable with a specific type
    int age = 25;

    // Error: Incompatible type assignment           
    age = "twenty-five";

    printf("Age: %d\n", age);
    return 0;
}
```

---

### Statically Typed Language Example (C++):

```cpp
#include <iostream>
using namespace std;

int main() {

    // Declaring a variable with a specific type
    int age = 25;

    // Error: Cannot assign a string to an integer        
    age = "twenty-five";

    cout << "Age: " << age << endl;
    return 0;
}
```

---

### Statically Typed Language Example (Java):

```java
public class Main {
    public static void main(String[] args) {

        // Declaring a variable with a specific type
        int age = 25;

        // Error: Incompatible types    
        age = "twenty-five";

        System.out.println("Age: " + age);
    }
}
```

---

### Dynamically Typed Language Example (Python):

```python

# Variable `age` is initially a number
age = 25

 # No error: Variable `age` is now a string            
age = "twenty-five"

 # Output: Age: twenty-five
print("Age:", age)     
```

---

### Dynamically Typed Language Example (JavaScript):

 ![Screenshot](i1.png)
