# Generic Stack Implementation in C++

A template-based stack implementation in C++ with a user-friendly, menu-driven interface. This project reinforces understanding of stack data structures, type generalization using templates, and basic input validation for secure operations.

## ✏️ Design
![project-2](https://github.com/user-attachments/assets/a7f58346-c438-478c-a99c-3ae0537c2d95)

## 📌 Project Overview

- Developed a generic `Stack<T>` class using C++ templates  
- Interactive CLI to perform stack operations such as:
   ```cpp
       push()
       pop()
       top()
       isEmpty()
       size()
    ```
- Fully type-generic: works with user-defined types (int, float, string, etc.)
- Basic input validation to avoid runtime misuse and simulate boundary cases
- Clear structure and modular code for ease of maintenance
- Defensive programming practices: checks for overflow/underflow

## 🧠 Concepts Applied

- Data Structures: Stack (LIFO)
- C++ Templates for generic programming
- Menu-based console UI using standard I/O
- Safety checks to prevent invalid operations (e.g., popping from an empty stack)

## 🛠️ Technologies Used

- C++ (Templates, OOP)
- Vi Editor
- CLI tools and standard library I/O

## 🧪 Sample Usage

```bash
********** Main Menu ***********
-----------------------------------
1. Push Element
2. Pop Element
3. View Top
4. Display Stack
5. Check Empty
6. Stack Size
7. Exit
Select option:
-----------------------------------
````

```cpp
Stack<int> intStack;
intStack.push(10);
intStack.push(20);
std::cout << intStack.top();  // Output: 20
intStack.pop();
std::cout << intStack.size(); // Output: 1
```

## 📁 Project Structure

```
.
├── Stack.hpp         # Template class declaration
├── main.cpp          # Menu-driven interface and test driver
└── Makefile          # Build system
```

---

This project demonstrates proficiency in C++ templates, OOP, and command-line application development—critical skills for system-level and backend development roles.

---


## Demonstration
![Screenshot 2025-05-16 035023](https://github.com/user-attachments/assets/ccb4fd30-8e10-46fc-b315-b37084ba3b47)
## 1. Push operation
![Screenshot 2025-05-16 035131](https://github.com/user-attachments/assets/82a26b6b-d97c-4268-9e8a-0cfba5f0ded8)
![Screenshot 2025-05-16 035203](https://github.com/user-attachments/assets/1d95d7c5-6951-43bf-b483-d1db1e2fb4ca)
## 3. Get top element and display stack
![Screenshot 2025-05-16 035235](https://github.com/user-attachments/assets/8aaa3c02-fa2a-41e3-b9a5-e8a704f7868d)
## 2. Pop operation
![Screenshot 2025-05-16 035323](https://github.com/user-attachments/assets/d9f65bdf-b87b-46b7-9e62-40013e35487c)

![Screenshot 2025-05-16 035346](https://github.com/user-attachments/assets/ab403271-a250-4adb-9d2a-67d901c01af8)

#### when user selects wrong option first times it warns, 2nd time also warns to select correct option and in 3rd times it exit from the program so that this avoid potential security issue.
![Screenshot 2025-05-16 040111](https://github.com/user-attachments/assets/01832a85-c48d-4bd6-81a8-fe3f965748be)
![Screenshot 2025-05-16 040210](https://github.com/user-attachments/assets/c4518c25-5164-4780-84e9-a413d5b75b24)
