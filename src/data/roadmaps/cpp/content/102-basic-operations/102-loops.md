# Loops in C++

Loops are an essential concept in programming that allow you to execute a block of code repeatedly until a specific condition is met. In C++, there are three main types of loops: `for`, `while`, and `do-while`.

## For Loop

A `for` loop is used when you know the number of times you want to traverse through a block of code. It consists of an initialization statement, a condition, and an increment/decrement operation.

Here's the syntax for a `for` loop:

```cpp
for (initialization; condition; increment/decrement) {
    // block of code to execute
}
```

For example:

```cpp
#include <iostream>

int main() {
    for (int i = 0; i < 5; i++) {
        std::cout << "Iteration: " << i << std::endl;
    }
    return 0;
}
```

## While Loop

A `while` loop runs as long as a specified condition is `true`. The loop checks for the condition before entering the body of the loop.

Here's the syntax for a `while` loop:

```cpp
while (condition) {
    // block of code to execute
}
```

For example:

```cpp
#include <iostream>

int main() {
    int i = 0;
    while (i < 5) {
        std::cout << "Iteration: " << i << std::endl;
        i++;
    }
    return 0;
}
```

## Do-While Loop

A `do-while` loop is similar to a `while` loop, with the key difference being that the loop body is executed at least once, even when the condition is `false`.

Here's the syntax for a `do-while` loop:

```cpp
do {
    // block of code to execute
} while (condition);
```

For example:

```cpp
#include <iostream>

int main() {
    int i = 0;
    do {
        std::cout << "Iteration: " << i << std::endl;
        i++;
    } while (i < 5);
    return 0;
}
```

In summary, loops are an integral part of C++ programming that allow you to execute a block of code multiple times. The three types of loops in C++ are `for`, `while`, and `do-while`. Each type has its own specific use case and can be chosen depending on the desired behavior.

# Additional Have more loops.
1. For Loop
Syntax:
for (initialization; condition; increment/decrement) {
    // Code
}

Example:
for (int i = 0; i < 5; i++) {
    cout << "Iteration: " << i << endl;
}

2. While Loop
Syntax:
while (condition) {
    // Code
}

Example:
int i = 0;
while (i < 5) {
    cout << "Iteration: " << i << endl;
    i++;
}

3. Do-While Loop
Syntax:
do {
    // Code
} while (condition);

Example:
int i = 0;
do {
    cout << "Iteration: " << i << endl;
    i++;
} while (i < 5);

4. Range-Based For Loop
Syntax:
for (declaration : container) {
    // Code
}

Example:
vector<int> numbers = {1, 2, 3, 4, 5};
for (int num : numbers) {
    cout << "Number: " << num << endl;
}

5. Nested Loops
Syntax:
for (initialization; condition; increment/decrement) {
    for (initialization; condition; increment/decrement) {
        // Code
    }
}

Example:
for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 3; j++) {
        cout << "i: " << i << ", j: " << j << endl;
    }
}

6. Infinite Loop
Syntax:
while (true) {
    // Code
}

Example:
while (true) {
    cout << "This will run forever!" << endl;
    // Use break to exit the loop if needed
}

7. Break Statement
Syntax:
break; // Exits the loop

Example:
for (int i = 0; i < 10; i++) {
    if (i == 5) {
        break; // Exit the loop when i is 5
    }
    cout << "i: " << i << endl;
}

8. Continue Statement
Syntax:
continue; // Skips the current iteration

Example:
for (int i = 0; i < 10; i++) {
    if (i % 2 == 0) {
        continue; // Skip even numbers
    }
    cout << "i: " << i << endl;
}

9. Labeled Loop
Syntax:
label: loop_type {
    // Code
}

Example:
outer_loop: for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 3; j++) {
        if (j == 1) {
            break outer_loop; // Breaks out of the outer loop
        }
        cout << "i: " << i << ", j: " << j << endl;
    }
}


Learn more from the following resources:

- [@article@C++ For Loop](https://www.w3schools.com/cpp/cpp_for_loop.asp)
