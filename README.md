# Hello World in C++

A simple C++ program that prints "Hello World" to the console. Written for a C++ programming assignment (CSC 207).

## Program

```cpp
#include <iostream>

int main() {
    std::cout << "Hello World" << std::endl;
    return 0;
}
```

## How it works

- `#include <iostream>` loads the input/output library.
- `int main()` is the function where every C++ program starts.
- `std::cout` prints the text to the screen.
- `return 0;` tells the computer the program finished successfully.

## How to run

1. Install a C++ compiler (this project used g++ from MSYS2 with VS Code).
2. Compile the program:
   ```
   g++ hello.cpp -o hello
   ```
3. Run it:
   ```
   ./hello
   ```

## Output

```
Hello World
```

## Author

Zakariya Ogundare
