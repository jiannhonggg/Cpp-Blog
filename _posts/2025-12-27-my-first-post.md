---
layout: post 
title: "Hello World"
date: 2025-12-28 10:00:00 +0800
category: [C++]
tags: [C++]
math: true 
toc: true #(Optional: false to hide the Table of Contents)
---

Welcome to my first official blog post! I am using this site to document everything I learn about **C++**. I will be using Abdul Bahri's Learn C++ From Beginner to Advanced as a guide. 

---

**Definitions and terminology:**

A **Computer** is a programmable computational device. 

A **Procedure** can be defined as a solution step given to a computer (program) which the CPU will execute and give the results.

A **Program** is a collection of data and a set of instructions. 

A **Programing Language** is essentially an intermediary language that translates natural language to machine code. 

C++ is considered a high-level language in contrast to low-level languages like Assembly and Machine Code. It is also a compiler-based language. 

**Compiler-Based Languages vs Interpreter-Based Languages:** 

Compiler
- Generate a separate machine code (executable)
- This compilation from source code to machine code is only done once.
- The compiler won't be there at the time of execution.
- If there is an error in the program, the program will not be compiled. 

Interpreter
- Does not generate an executable file for execution. 
- Source code is translated and executed line by line. 
- Translation is done again and again. 

A Compiler is faster than an interpreter.

In an interpreter, if there is an error in one line, the code will still execute up to that line. 

--- 

**Primitive Data Types**
Primitive data type are basic data types of C++

There are 3 types: integral, bool, floating point

| Data Type | Size | Range | 
| -------- | ------- | ---- |
| int  | 2 or 4 | -32768 - 32767 |
| float | 4 | -3.4 x $10^{-38}$ - 3.4 x $10^{38}$ | 
| double | 8 | -1.7 x $10^{-308} $ - 1.7 x $10^{308}$ | 
| char | 1 | -128 - 127 | 
| bool | undefine | True / False | 

--- 

**A Baisc Hello World Program:** 

Now that we got the definitions and terminology out of the way, let's begin coding ! 

```cpp
#include <iostream> 

int main() {
    std::cout << "Hello, World! I am learning C++." << std::endl;
    return 0;
}
```

**`int main()`**: The **main function**. It is the designated starting point where the execution of the program begins. Every C++ program must have this.

**`#include <iostream>`**: The **header file** (library) that provides the tools for handling input and output data streams.

**`std::cout`**: Stands for **Character Output**. It is an object that represents the standard output stream, typically used to display text to the console.

**`<<`**: The **insertion operator**. It "inserts" or "points" the data on its right into the output stream on its left.

**`std`**: The **Standard Namespace**. It acts as a container for all standard C++ functions and objects, preventing naming conflicts with your own code.
