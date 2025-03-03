# Flowchart and Pseudocode - Example 3

This example demonstrates how to determine whether a number is **odd or even** using both a **flowchart** and **pseudocode**.

---

## Problem Statement:

- Given an integer `n`, determine whether it is **even** or **odd** using the modulus (`%`) operator.

---

## Flowchart:

```
      +---------+
      |  Start  |
      +---------+
           |
           v
  +----------------+
  |  Input value n |
  +----------------+
           |
           v
  +----------------+
  |  n % 2 == 0 ?  |
  +----------------+
       /    \
      /      \
   Yes        No
   |          |
   v          v
+--------+  +--------+
| Print  |  | Print  |
|  Even  |  |  Odd   |
+--------+  +--------+
   \        /
    \      /
     v    v
  +---------+
  |  Exit   |
  +---------+

```

## Pseudocode:

```plaintext
Start

Input value (n)

If n % 2 == 0

Then

    Print "Even Number"

Else

    Print "Odd Number"

End If

Exit
