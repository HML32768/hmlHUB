# Vectors
### Initialization

```C++
#include <vectors>
// All STL components are in the std namespace. So we can use
usnig namespace std;
// instead of std::..
```

### Declaring a Vector
```C++
vector<datatype>vectorName();

// For example, creating an empty vector:
vector<string>vectorName();
// Declare one with a size = 5:
vector<string>vectorName(5);
// Initialize all of a vector’s elements to the same value:
vector<string>vectorName(5, "value");
// Declare a vector and initialize it with the contents of another vector myVector:
vector<string>vectorName(myVector);
```

### Functions
```C++
// Adds a new element to the end of a vector:
vectorName.push_back(value);
// Removes the last element of a vector, size--:
vectorName.pop_back();
//Function returns the size of a vector:
vectorName.size();
// Removes all of the items of a vector, size = 0:
vectorName.clear();
// Rturns true if the vector object is empty:
vectorName.empty();
```

### Indexing
```C++
// Assign a new value to an EXISTING element position:
myVector[i] = value;
```




