## Simple Examples

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

### Dynamically Typed Language Example (JavaScript):

 ![Screenshot](i1.png)
