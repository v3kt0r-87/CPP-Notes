# How Code Runs - C++ Compilation Process

Understanding how **C++ code** is written, compiled, and executed.

---

## Steps of Code Execution:

1. **Writing Code:**
   - C++ code is written inside an **IDE (Integrated Development Environment)** such as:
     - **VS Code**
     - **Visual Studio**
     - **Other Editors**

2. **Compilation Process:**
   - The C++ code is translated into **binary (010101)** using a compiler.

3. **Types of Compilers:**
   - There are two main C++ compilers:
     - `g++` (GNU Compiler Collection)
     - `clang++` (LLVM-based compiler)

4. **Best Compiler Choices:**
   - `g++` is widely used in **Linux**.
   - `MinGW` is used for compiling C++ on **Windows**.

---

## Diagram Representation:

```plaintext
C++ Code  --->  IDE  --->  Editor (VS Code, Visual Studio)  
      \   
       \-> Compiler (g++ / clang++)  --->  Binary Executable (010101)
