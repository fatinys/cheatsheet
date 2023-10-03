# Sheet

### Nested Loop

```cpp
int main() {
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 2; j++) {
            std::cout << "(" << i << "," << j << ") ";
        }
        std::cout << std::endl;
    }
    return 0;
}
```
  
    Output:
    (0,0) (0,1) 
    (1,0) (1,1) 
    (2,0) (2,1)

### Switch
```cpp
  switch (grade) {
        case 'A':
            std::cout << "Excellent!" << std::endl;
            break;
        default:
            std::cout << "Invalid grade." << std::endl;
    }
```
### Conditional Expression
```cpp
    std::string message = (age >= 18) ? "You are an adult." : "You are not yet an adult.";
```
### Character Access
```cpp
    std::string str = "Hello";
    char firstChar = str[0];
    char lastChar = str[str.length() - 1];
```
### Modify Strings
```cpp
    std::string str = "Hello";
    // Append
    str.append(" World");
    // Insert
    str.insert(5, " C++");
    // Erase
    str.erase(0, 6); // Removes "Hello "
    // Replace
    str.replace(0, 5, "Hi");
```
### Arrays
```cpp
// Declaration (specify data type and size)
int myArray[5];
// Definition and Initialization
int numbers[3] = {1, 2, 3}; // Explicit initialization
int scores[] = {95, 80, 70}; // Size inferred from initializer
// Multidimensional Array
int matrix[2][3] = {{1, 2, 3}, {4, 5, 6}};
```
### String Cat and Copy
```cpp
strcpy(result, str1); // Copy str1 to result
strcat(result, str2); // Concatenate str2 to result
```
### Paralell Array
```cpp
int studentIds[] = {101, 102, 103, 104};
string studentNames[] = {"Alice", "Bob", "Charlie", "David"};
double studentGrades[] = {90.5, 85.0, 78.5, 92.0};
```
### Exceptions
```cpp
if (errorCondition) {
    throw MyException("Something went wrong");
}
```
### Catching an Exception
```cpp
try {
    // Code that may throw an exception
} catch (MyException& e) {
    // Handle MyException
}
```




















