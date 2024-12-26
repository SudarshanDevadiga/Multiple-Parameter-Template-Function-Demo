# Multiple Parameter Template Function Demo

A C++ program demonstrating a template function that can handle two different data types as parameters and display them together.

## Description

This program implements a template function `display()` with two different type parameters, showing how template functions can handle multiple data types simultaneously. It's a simple but effective demonstration of template flexibility in C++.

### Key Features
- Template function with two type parameters
- Multiple data type handling
- Flexible output formatting
- Simple implementation

## Function Template Structure

```cpp
template <class T1, class T2>
void display(T1 x, T2 y)
{
    cout << x << "" << y << "\n";
}
