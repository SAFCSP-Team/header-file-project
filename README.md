# Header File Project

### Objective
Understand how to work with header file in C++.

### Problem
Create a simple C++ program that uses **header files** to perform basic arithmetic operations (addition, subtraction, multiplication, and division).

### Implementation
1. Create the **header** File with the name **calculator.h**, this file will include the below functions
   - add(int a, int b)
   - subtract(int a, int b)
   - multiply(double a, double b)
   - divide(double a, double b)
2. Create the Implementation file named **calculator.cpp**, this file should have the implementation details for the all functions in the header file **calculator.h**.
3. Create a file named **main.cpp** and add the following code
```c++
int main() {
    calculator calc;
    int a = 10, b = 5;

    std::cout << "Addition: " << calc.add(a, b) << std::endl;
    std::cout << "Subtraction: " << calc.subtract(a, b) << std::endl;
    std::cout << "Multiplication: " << calc.multiply(a, b) << std::endl;
    std::cout << "Division: " << calc.divide(a, b) << std::endl;

    return 0;
}
```
4. Compile the Code.
5. Link the Object File.
6. Execute the Program.

Expected Output
```
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2
```
