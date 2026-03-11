# Data Structures & Algorithms (DSA0117) - Assignment 3

**Author:** DUSYAANT R  
**Registration No:** 192465058  
**Course ID:** DSA0117  

This repository contains the third installment of C++ programs for the **DSA0117** curriculum. This set focuses on Object-Oriented Programming (OOP) paradigms, memory management, and advanced bitwise/array logic.

## 📂 Included Programs (5 total)

1.  **Multiple Inheritance System:** 
    *   **Classes:** `Person` + `Employee` → `DisplayInfo`.
    *   **Concept:** Demonstrates how a derived class can inherit and aggregate data from multiple base classes simultaneously.

2.  **Access Specifier Demonstration:** 
    *   **Keywords:** `public`, `private`, and `protected`.
    *   **Concept:** Illustrates the boundaries of member visibility within a class hierarchy and prevents unauthorized access to private data.

3.  **Local Variable Modification (Pointers):** 
    *   **Mechanism:** Pass-by-address.
    *   **Concept:** Shows how to use pointers to modify the local variables of `main()` from within a separate `modifyValues()` function.

4.  **Pointer Arithmetic & Array Indexing:** 
    *   **Mechanism:** Memory offsets.
    *   **Concept:** Visualizes how the compiler translates `arr[i]` into `*(ptr + i)` by displaying hexadecimal memory addresses and data values.

5.  **N-th Fibonacci Number (Recursive/Iterative):** 
    *   **Logic:** If-Else Ladder.
    *   **Concept:** Calculates the sequence up to index $N$ while handling edge cases like negative numbers, decimals (3.5), and non-numeric inputs (A).

## 🚀 How to Run

### Compilation
Use a standard C++ compiler like `g++`:
```bash
g++ FileName.cpp -o ProgramOutput
