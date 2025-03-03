# 📌 How Code Runs (C++)

This section explains how C++ code is **compiled and executed** on different operating systems.

---

## 🔹 Compilation Process:

1. **Write Source Code (`.cpp` file)**
2. **Use a Compiler (`g++` / `clang++`)**
3. **Generate an Executable (`.exe` on Windows, `a.out` on Linux)**
4. **Run the Executable**

---

## 💻 Compilation Commands:

### ✅ Windows:

```sh
g++ test.cpp

Output -> a.exe
```
### ✅ Linux/Unix:
```sh
g++ test.cpp

Output -> a.out
```

## ⚙️ Why Compile?
- Checks for errors/mistakes before execution.
- Builds an executable that can run on the system.
- Note: C++ is platform-dependent, meaning executables built on one OS may not work on another.



## Key Concepts:
- C++ is case-sensitive (e.g., Var and var are different).
- Every program starts with main() function.
- Includes header files (e.g., <iostream>).
- Uses cout for output.

### ✅ Example Code:
```
#include <iostream>  // Compiler directive
using std::cout;     // Avoids using namespace std

int main()
{
    cout << "Hello \n" ;
    return 0 ;  // Optional in `main()`
}
```
## ❌ Bad Practice:
- 🚫 Avoid using namespace std; It can cause naming conflicts in large projects.

---



