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

