# OOPS Elective – C++ Programs

This repository contains the C++ programs developed as part of my **Object-Oriented Programming (OOPS) Elective** coursework.

The programs progress from basic C++ programming concepts to classes, constructors, static members, friend functions, and inheritance.

---
---

## 👨‍🎓 Student Details

| Field        | Details             |
| ------------ | ------------------- |
| **Name**     | Kingson P Caleb D N |
| **Roll No.** | 632                 |
| **Division** | F                   |
| **SRN**      | 01FE23BEC331        |
| **Semester** | VII                 |

---

## 📁 Repository Structure

```text
OOPS_Elective_Programs/
│
├── Programs/
│   ├── Class_1/
│   ├── Class_2/
│   ├── Class_3/
│   ├── Class_4/
│   ├── Class_5/
│   ├── Class_6/
│   └── class_7/
│
├── Screenshots of errors/
│
├── .gitignore
└── README.md
```

Each class folder contains the programs covered during that respective class/session.

---

## 📚 Class-wise Programs

### Class 1 – C++ Fundamentals

Programs covering basic C++ syntax, input/output, data types, strings, and parameter passing.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Basic output using `cout` |
| `prog_2.cpp` | User input and addition of two numbers |
| `prog_3.cpp` | Basic data types and variable declaration |
| `prog_4.cpp` | Area of a rectangle using user input |
| `prog_5.cpp` | Finding the largest number in a list |
| `prog_6.cpp` | Finding string length using C-style and C++-style approaches |
| `prog_7.cpp` | C-style string palindrome checking |
| `prog_8.cpp` | C++-style palindrome program – incomplete practice program |
| `prog_9.cpp` | Parameter passing – pass by value |
| `prog_10.cpp` | Parameter passing – pass by reference |
| `prog_11.cpp` | Parameter passing – pass by pointer |

---

### Class 2 – Classes and Objects

Introduction to classes, objects, member functions, and defining functions outside a class.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Creating a class and object; accessing private data through member functions |
| `prog_2.cpp` | Student class with data members and member functions |
| `prog_3.cpp` | Defining a class member function outside the class |
| `prog_4.cpp` | Rectangle class with member functions for setting values and calculating area |
| `prog_5.cpp` | Improved Rectangle program with a function returning the calculated area |

---

### Class 3 – Member Functions and Constructors

Programs covering class-based data handling, object interaction, and constructors.

| Program | Concept |
|---|---|
| `prog_1.cpp` | `Time` class and addition of two time objects |
| `prog_2.cpp` | Addition of two complex numbers using objects |
| `prog_3.cpp` | Default constructor for initializing employee data |
| `prog_4.cpp` | Default and parameterized constructors |
| `prog_5.cpp` | Parameterized constructor using a `Distance` class |
| `prog_6.cpp` | Default, parameterized, and copy constructors |

---

### Class 4 – Destructors and Static Data Members

Programs demonstrating object destruction and static members shared among objects.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Destructor with a class having default, parameterized, and copy constructors |
| `prog_2.cpp` | Static data member shared by multiple objects |
| `prog_3.cpp` | Static counter with a separate employee ID for each object |

> **Note:** `prog_2.cpp` and `prog_3.cpp` are intended to be compared to understand how static data members behave when they are shared by all objects of a class.

---

### Class 5 – Static Member Functions and Friend Functions

Programs covering static member functions and access to private class members through friend functions.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Static member function and static data member |
| `prog_2.cpp` | Friend function accessing private members of a class |
| `prog_3.cpp` | Practice program for friend function parameters |
| `prog_4.cpp` | Common friend function accessing private data from two classes |

---

### Class 6 – Inheritance

Introduction to inheritance and multi-level inheritance.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Single-level inheritance using `Animal` and `Dog` |
| `prog_2.cpp` | Multi-level inheritance using `Person`, `Student`, and `IT_Student` |
| `prog_3.cpp` | Multi-level inheritance and experimentation with access modes |

---

### Class 7 – Multi-level Inheritance and Access Control

Further practice with multi-level inheritance and the `protected` access specifier.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Multi-level inheritance using `Vehicle`, `Car`, and `Sports Car` |
| `prog_2.cpp` | Multi-level inheritance using `protected` members |
| `prog_3.cpp` | Reserved for further practice |

---

## 🧠 Concepts Covered

The repository covers the following C++ and OOPS concepts:

- Basic C++ syntax
- Input and output using `cin` and `cout`
- Variables and data types
- Functions
- Parameter passing
  - Pass by value
  - Pass by reference
  - Pass by pointer
- Strings
- Classes and objects
- Data members and member functions
- Member functions defined outside a class
- Constructors
  - Default constructor
  - Parameterized constructor
  - Copy constructor
- Destructors
- Static data members
- Static member functions
- Friend functions
- Friend functions involving multiple classes
- Single-level inheritance
- Multi-level inheritance
- Access specifiers
  - `private`
  - `public`
  - `protected`

---

## 💻 Programming Language

**C++**

The programs use standard C++ features and headers such as:

```cpp
#include <iostream>
#include <cstring>
```

---

## 🛠️ Tools Used

- **C++**
- **GCC / G++ compiler**
- **Visual Studio Code**
- **Git**
- **GitHub**

---

## ▶️ How to Run

### Option 1: Run using Code::Blocks

The programs can be compiled and executed using **Code::Blocks** with a C++ compiler.

1. Open **Code::Blocks**.
2. Go to **File → Open** and select the required `.cpp` file.
3. If Code::Blocks asks for a compiler, select/configure the installed **GCC / MinGW** compiler.
4. Open the program you want to execute.
5. Click **Build and Run** or press:

```text
F9
```

6. The program output will appear in the **Console** window.

For example, to run:

```text
Programs/
└── Class_1/
    └── prog_1.cpp
```

Open `prog_1.cpp` in Code::Blocks and use **Build → Build and Run**.

> **Note:** Most of these programs are standalone `.cpp` files, so they can be opened and run individually without creating a large project containing all programs.

### Option 2: Run using Visual Studio Code

Open the repository folder in Visual Studio Code.

Compile a program using G++:

```bash
g++ Programs/Class_1/prog_1.cpp -o program
```

Run the compiled program on Windows:

```bash
program.exe
```

Or, depending on the terminal:

```bash
./program
```

You can replace the file path with any `.cpp` program you want to execute.

### Option 3: Clone the repository first

```bash
git clone https://github.com/king-3333333/OOPS_Elective_Programs.git
```

Then open the cloned folder in **Code::Blocks, Visual Studio Code, or another C++ IDE**.

---

## 📸 Screenshots / Errors

The `Screenshots of errors` folder contains screenshots related to errors encountered while developing and testing the programs.

These are included as part of the learning and debugging process.

---

## 📌 Notes

Some programs are intentionally kept in their original coursework/practice form. A few files contain incomplete experiments or code written while exploring a particular concept.

The repository is primarily intended for **coursework, learning, practice, and revision of C++ OOPS concepts**.

---

## 👨‍💻 Author

**Kingson Caleb**

Electronics and Communication Engineering (ECE)

---

⭐ If this repository is useful for learning C++ OOPS concepts, feel free to star the repository.
