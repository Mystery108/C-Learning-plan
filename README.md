# C++-Learning-plan
# C++ Learning Roadmap: 30-Day Detailed Plan

This document outlines a structured C++ learning plan from basic to advanced topics, including daily topics, curated video and website resources, practice ideas, and project suggestions. Use this as a guide to build your knowledge step-by-step.

---

## Table of Contents

- [Overview](#overview)
- [Week 1: Basics & Foundations](#week-1-basics--foundations)
  - [Day 1: Introduction to C++ & Environment Setup](#day-1-introduction-to-c--environment-setup)
  - [Day 2: Variables, Data Types, Input/Output](#day-2-variables-data-types-inputoutput)
  - [Day 3: Operators & Expressions](#day-3-operators--expressions)
  - [Day 4: Control Flow: If, Else, Switch](#day-4-control-flow-if-else-switch)
  - [Day 5: Loops: For, While, Do-While](#day-5-loops-for-while-do-while)
  - [Day 6: Functions](#day-6-functions)
  - [Day 7: Practice Problems](#day-7-practice-problems)
- [Week 2: Intermediate Concepts](#week-2-intermediate-concepts)
  - [Day 8: Arrays & Strings](#day-8-arrays--strings)
  - [Day 9: Vectors & Introduction to STL](#day-9-vectors--introduction-to-stl)
  - [Day 10: Pointers](#day-10-pointers)
  - [Day 11: References & Dynamic Memory](#day-11-references--dynamic-memory)
  - [Day 12: Advanced Functions (Overloading & Recursion)](#day-12-advanced-functions-overloading--recursion)
  - [Day 13: Structs & Enums](#day-13-structs--enums)
  - [Day 14: Practice & Mini Project](#day-14-practice--mini-project)
- [Week 3: Object-Oriented Programming (OOP)](#week-3-object-oriented-programming-oop)
  - [Day 15: Classes & Objects](#day-15-classes--objects)
  - [Day 16: Constructors & Destructors](#day-16-constructors--destructors)
  - [Day 17: Encapsulation & Access Specifiers](#day-17-encapsulation--access-specifiers)
  - [Day 18: Inheritance](#day-18-inheritance)
  - [Day 19: Polymorphism & Virtual Functions](#day-19-polymorphism--virtual-functions)
  - [Day 20: Friend Functions & Operator Overloading](#day-20-friend-functions--operator-overloading)
  - [Day 21: OOP Practice Project](#day-21-oop-practice-project)
- [Week 4: Advanced Topics & STL](#week-4-advanced-topics--stl)
  - [Day 22: Exception Handling](#day-22-exception-handling)
  - [Day 23: File I/O](#day-23-file-i-o)
  - [Day 24: Templates (Function & Class Templates)](#day-24-templates-function--class-templates)
  - [Day 25: Smart Pointers](#day-25-smart-pointers)
  - [Day 26: Lambda Functions, Auto, Range-based For Loops](#day-26-lambda-functions-auto-range-based-for-loops)
  - [Day 27: STL Deep Dive: Maps, Sets, Queues, Stacks](#day-27-stl-deep-dive-maps-sets-queues-stacks)
  - [Day 28: Data Structures with STL—Practice](#day-28-data-structures-with-stlpractice)
- [Week 5: Projects & Next Steps](#week-5-projects--next-steps)
  - [Day 29: Capstone Project](#day-29-capstone-project)
  - [Day 30: Review, Debugging, and Next Steps](#day-30-review-debugging-and-next-steps)
- [Additional Tips for Success](#additional-tips-for-success)
- [Converting Markdown to PDF](#converting-markdown-to-pdf)

---

## Overview

**Duration:** 30 Days (adjust based on your pace)  
**Goal:** To learn C++ from basics to advanced concepts using high-quality video and web resources.  
**Structure:**  
- **Week 1:** Focus on core programming fundamentals  
- **Week 2:** Intermediate C++ concepts and standard library usage  
- **Week 3:** Object-Oriented Programming in C++  
- **Week 4:** Advanced topics in C++ and a deep dive into the STL  
- **Week 5:** Capstone project and review

---

## Week 1: Basics & Foundations

### Day 1: Introduction to C++ & Environment Setup

**Topics Covered:**
- Overview of C++
- Setting up the development environment
- Writing your first "Hello World" program

**Resources:**

- **Video:**  
  [C++ Programming for Beginners (up to 35 min) – CodeBeauty](https://youtu.be/vLnPwxZdW4Y)

- **Reading:**  
  [LearnCpp.com – Introduction to C++](https://www.learncpp.com/cpp-tutorial/introduction-to-c/)

- **Development Setup:**  
  - **Online:**  
    - [Programiz Online C++ Compiler](https://www.programiz.com/cpp-programming/online-compiler)  
    - [OnlineGDB C++ Compiler](https://www.onlinegdb.com/online_c++_compiler)
  - **Local Installation:**  
    - **Windows:** Use Code::Blocks or Visual Studio Code with MinGW  
    - **Mac:** Use Xcode or install GCC via Homebrew (`brew install gcc`)  
    - **Linux:** Install via package manager (e.g., `sudo apt-get install g++`)

**Example Code:**

```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

**Practice Tasks:**
- Modify the "Hello World" code to print your name.
- Add code to print two lines of text using `std::cout`.

---

### Day 2: Variables, Data Types, & Input/Output

**Topics Covered:**
- Understanding variables and data types
- Working with basic I/O in C++

**Resources:**

- **Reading:**  
  [LearnCpp.com – Variables and Basic Types](https://www.learncpp.com/cpp-tutorial/variables-and-basic-types/)

- **Video:**  
  [C++ Input/Output Video – freeCodeCamp](https://youtu.be/vLnPwxZdW4Y?t=2130) (watch approximately the next 20 minutes)

**Practice Tasks:**
- Write a program that declares different types of variables (int, float, char, etc.) and prints them.
- Use `std::cin` to accept input and `std::cout` to display output.

---

### Day 3: Operators & Expressions

**Topics Covered:**
- Arithmetic, relational, logical, and assignment operators
- Forming expressions

**Resources:**

- **Reading:**  
  [LearnCpp.com – Arithmetic Operators](https://www.learncpp.com/cpp-tutorial/arithmetic-operators/)

- **Video:**  
  [C++ Operators Video](https://youtu.be/vLnPwxZdW4Y?t=4200) (watch for about 15 minutes)

**Practice Tasks:**
- Create a program that calculates the area of a circle given its radius.
- Experiment with increment/decrement operators and observe the effects.

---

### Day 4: Control Flow – If, Else, Switch

**Topics Covered:**
- Conditional statements (`if`, `else`, `switch`)

**Resources:**

- **Reading:**  
  [LearnCpp.com – Selection Statements: If and Switch](https://www.learncpp.com/cpp-tutorial/selection-statements-if-and-switch/)

- **Video:**  
  [C++ Control Flow Video](https://youtu.be/vLnPwxZdW4Y?t=5100) (approximately 20 minutes)

**Practice Tasks:**
- Write a program that uses if/else to check if a number is positive, negative, or zero.
- Use a switch statement to convert numerical input into a simple menu.

---

### Day 5: Loops – For, While, Do-While

**Topics Covered:**
- Loop constructs

**Resources:**

- **Reading:**  
  [LearnCpp.com – Loops and Iteration](https://www.learncpp.com/cpp-tutorial/loops-and-iteration/)

- **Video:**  
  [C++ Loops Video](https://youtu.be/vLnPwxZdW4Y?t=6300) (watch for about 25 minutes)

**Practice Tasks:**
- Create programs that use each loop type to print a series of numbers.

---

### Day 6: Functions

**Topics Covered:**
- Declaring and calling functions
- Function parameters and return types

**Resources:**

- **Reading:**  
  [LearnCpp.com – Introduction to Functions](https://www.learncpp.com/cpp-tutorial/introduction-to-functions/)

- **Video:**  
  [C++ Functions Video](https://youtu.be/vLnPwxZdW4Y?t=7800) (approximately 25 minutes)

**Practice Tasks:**
- Write a function to calculate the factorial of a number.
- Experiment with functions that return different types of values.

---

### Day 7: Practice Problems

**Topics Covered:**
- Reinforcement of Week 1 concepts through practice

**Resources:**

- **Practice Platforms:**  
  - [HackerRank C++ Practice](https://www.hackerrank.com/domains/tutorials/10-days-of-cpp)  
  - [Exercism C++ Track](https://exercism.org/tracks/cpp)

**Practice Tasks:**
- Solve multiple coding challenges and small problems to apply what you have learned.

---

## Week 2: Intermediate Concepts

### Day 8: Arrays & Strings

**Topics Covered:**
- Definition and use of arrays
- Basics of C-string and C++ string objects

**Resources:**

- **Reading:**  
  [LearnCpp.com – Arrays Part I](https://www.learncpp.com/cpp-tutorial/arrays-part-i/)

- **Video:**  
  [C++ Arrays Video](https://youtu.be/vLnPwxZdW4Y?t=9300) (about 20 minutes)

**Practice Tasks:**
- Write a program that stores and prints a list of names using an array.
- Experiment with C++ string manipulation functions.

---

### Day 9: Vectors & Introduction to STL

**Topics Covered:**
- Utilizing dynamic arrays with vectors
- Basic introduction to the Standard Template Library (STL)

**Resources:**

- **Reading:**  
  [LearnCpp.com – Introduction to std::vector](https://www.learncpp.com/cpp-tutorial/an-introduction-to-stdvector/)

- **Video:**  
  [C++ STL Video](https://youtu.be/1v_4dL8l5XA)

**Practice Tasks:**
- Create, add, and remove elements in a vector.
- Use STL algorithms like `std::sort` on a vector of integers.

---

### Day 10: Pointers

**Topics Covered:**
- Basics of pointers and memory addresses
- Pointer arithmetic and usage

**Resources:**

- **Reading:**  
  [LearnCpp.com – Introduction to Pointers](https://www.learncpp.com/cpp-tutorial/introduction-to-pointers/)

- **Video:**  
  [C++ Pointers Video](https://youtu.be/mUQZ1qmKlLY)

**Practice Tasks:**
- Write a program that demonstrates pointer assignment and dereferencing.
- Explore how pointers can be used to modify variable values.

---

### Day 11: References & Dynamic Memory

**Topics Covered:**
- Difference between pointers and references
- Dynamic memory allocation using `new` and `delete`

**Resources:**

- **Reading:**  
  [LearnCpp.com – References](https://www.learncpp.com/cpp-tutorial/references/)
  
- **Video:**  
  [C++ Dynamic Memory Video](https://youtu.be/DTxHyVn0ODg)

**Practice Tasks:**
- Create functions that use references to swap two variables.
- Dynamically allocate an array and properly deallocate it after use.

---

### Day 12: Advanced Functions (Overloading & Recursion)

**Topics Covered:**
- Function overloading
- Recursion and its use cases

**Resources:**

- **Reading:**  
  [LearnCpp.com – Function Overloading](https://www.learncpp.com/cpp-tutorial/function-overloading/)
  
  [LearnCpp.com – Recursion](https://www.learncpp.com/cpp-tutorial/recursion/)

**Practice Tasks:**
- Overload functions for different parameter types.
- Write a recursive function to compute the Fibonacci series.

---

### Day 13: Structs & Enums

**Topics Covered:**
- Defining and using structures (`struct`)
- Creating and using enumerated types (`enum`)

**Resources:**

- **Reading:**  
  [LearnCpp.com – Structs](https://www.learncpp.com/cpp-tutorial/structs/)
  
  [LearnCpp.com – Enums](https://www.learncpp.com/cpp-tutorial/enumerations/)

**Practice Tasks:**
- Define a struct to represent a simple student record.
- Use enum types to list constant values and switch on them.

---

### Day 14: Practice & Mini Project

**Topics Covered:**
- Apply intermediate concepts with a mini project

**Resources:**

- **Project Ideas:**  
  [GeeksforGeeks C Projects](https://www.geeksforgeeks.org/c-projects/)

- **Practice Task:**  
  Build a simple calculator or a small game to reinforce your understanding.

---

## Week 3: Object-Oriented Programming (OOP)

### Day 15: Classes & Objects

**Topics Covered:**
- Defining classes and creating objects in C++
- Understanding class members and methods

**Resources:**

- **Reading:**  
  [LearnCpp.com – Classes and Class Members](https://www.learncpp.com/cpp-tutorial/classes-and-class-members/)

- **Video:**  
  [C++ OOP Video](https://youtu.be/x5Fi2FfVA0I)

**Practice Tasks:**
- Design a basic class (e.g., `Car`) with attributes and methods and instantiate objects.

---

### Day 16: Constructors & Destructors

**Topics Covered:**
- Role of constructors and destructors
- Initialization of objects

**Resources:**

- **Reading:**  
  [LearnCpp.com – Constructors and Initialization of Classes](https://www.learncpp.com/cpp-tutorial/constructors-and-initialization-of-classes/)

- **Video:**  
  [C++ Constructors Video](https://youtu.be/0vJJkIlBzEw)

**Practice Tasks:**
- Create a class with a constructor that sets initial values and a destructor to free resources.

---

### Day 17: Encapsulation & Access Specifiers

**Topics Covered:**
- Understanding public, private, and protected access modifiers
- Using access functions for encapsulation

**Resources:**

- **Reading:**  
  [LearnCpp.com – Access Functions and Encapsulation](https://www.learncpp.com/cpp-tutorial/access-functions-and-encapsulation/)

- **Video:**  
  [C++ Encapsulation Video](https://youtu.be/1v_4dL8l5XA?t=1800)

**Practice Tasks:**
- Update your class from previous days to enforce encapsulation.

---

### Day 18: Inheritance

**Topics Covered:**
- Deriving new classes from existing ones
- Understanding base and derived class relationships

**Resources:**

- **Reading:**  
  [LearnCpp.com – Basic Inheritance in C++](https://www.learncpp.com/cpp-tutorial/basic-inheritance-in-c/)

- **Video:**  
  [C++ Inheritance Video](https://youtu.be/0eYi0IPQJ6Y)

**Practice Tasks:**
- Create a base class (e.g., `Animal`) and derive specific classes (e.g., `Dog`, `Cat`) from it.

---

### Day 19: Polymorphism & Virtual Functions

**Topics Covered:**
- The concept of polymorphism and virtual functions
- Dynamic binding and method overriding

**Resources:**

- **Reading:**  
  [LearnCpp.com – Polymorphism and Virtual Functions](https://www.learncpp.com/cpp-tutorial/polymorphism-and-virtual-functions/)

- **Video:**  
  [C++ Polymorphism Video](https://youtu.be/pTB0EiLXUC8)

**Practice Tasks:**
- Use inheritance to create a polymorphic function that calls different implementations of the same function.

---

### Day 20: Friend Functions & Operator Overloading

**Topics Covered:**
- Implementing friend functions for class access
- Overloading operators for custom classes

**Resources:**

- **Reading:**  
  [LearnCpp.com – Friend Functions and Classes](https://www.learncpp.com/cpp-tutorial/friend-functions-and-classes/)  
  [LearnCpp.com – Operator Overloading](https://www.learncpp.com/cpp-tutorial/operator-overloading/)

**Practice Tasks:**
- Overload the `+` operator for a custom class (e.g., adding two complex numbers).

---

### Day 21: OOP Practice Project

**Topics Covered:**
- Applying all OOP concepts in a real project

**Project Ideas:**  
- Build a simple bank management system or a student database system.

---

## Week 4: Advanced Topics & STL

### Day 22: Exception Handling

**Topics Covered:**
- Throwing, catching, and handling exceptions in C++

**Resources:**

- **Reading:**  
  [LearnCpp.com – Basic Exception Handling](https://www.learncpp.com/cpp-tutorial/exceptions-basic-usage-and-throwing-exceptions/)

- **Video:**  
  [C++ Exceptions Video](https://youtu.be/8AZ8GqW5iak)

**Practice Tasks:**
- Write code that uses try/catch to handle potential errors from user input.

---

### Day 23: File I/O

**Topics Covered:**
- Reading from and writing to files using C++ streams

**Resources:**

- **Reading:**  
  [LearnCpp.com – Basic File I/O](https://www.learncpp.com/cpp-tutorial/basic-file-io/)

- **Video:**  
  [C++ File Handling Video](https://youtu.be/5kueYVvZs8A)

**Practice Tasks:**
- Create a program that writes data to a file and then reads from it.

---

### Day 24: Templates (Function & Class Templates)

**Topics Covered:**
- Writing generic functions and classes using templates

**Resources:**

- **Reading:**  
  [LearnCpp.com – Function Templates](https://www.learncpp.com/cpp-tutorial/function-templates/)

- **Video:**  
  [C++ Templates Video](https://youtu.be/_bYFu9mBnr4)

**Practice Tasks:**
- Implement a function template for swapping values.
- Create a simple class template (e.g., for a container).

---

### Day 25: Smart Pointers

**Topics Covered:**
- Introduction to smart pointers (`std::unique_ptr`, `std::shared_ptr`, etc.)

**Resources:**

- **Reading:**  
  [LearnCpp.com – An Introduction to Smart Pointers](https://www.learncpp.com/cpp-tutorial/an-introduction-to-smart-pointers/)

- **Video:**  
  [C++ Smart Pointers Video](https://youtu.be/UOB7-B2MfwA)

**Practice Tasks:**
- Rewrite a program that uses raw pointers to use smart pointers instead.

---

### Day 26: Lambda Functions, Auto, Range-based For Loops

**Topics Covered:**
- Using lambda expressions for inline functions
- Exploring type inference with `auto`
- Using range-based for loops

**Resources:**

- **Reading:**  
  [LearnCpp.com – Introduction to Lambdas](https://www.learncpp.com/cpp-tutorial/introduction-to-lambdas/)

- **Video:**  
  [C++ Lambdas Video](https://youtu.be/JwSS70SZdyM)

**Practice Tasks:**
- Write a lambda function to filter elements in a vector.
- Use range-based loops and `auto` in your code examples.

---

### Day 27: STL Deep Dive: Maps, Sets, Queues, Stacks

**Topics Covered:**
- Working with various STL containers

**Resources:**

- **Reading:**  
  [LearnCpp.com – Overview of the Standard Library Containers](https://www.learncpp.com/cpp-tutorial/overview-of-the-standard-library-containers/)

- **Video:**  
  [STL Video](https://youtu.be/1v_4dL8l5XA?t=1800)

**Practice Tasks:**
- Create programs that use maps, sets, queues, and stacks for different tasks.

---

### Day 28: Practice: Data Structures with STL

**Topics Covered:**
- Applying STL containers to solve problems

**Resources:**

- **Practice Platforms:**  
  - [LeetCode C++ Problems](https://leetcode.com/problemset/all/?topicSlugs=cpp)  
  - [HackerRank C++ Tutorials](https://www.hackerrank.com/domains/tutorials/10-days-of-cpp)

**Practice Tasks:**
- Solve problems that require the use of one or more STL containers.

---

## Week 5: Projects & Next Steps

### Day 29: Capstone Project

**Topics Covered:**
- Integrate all learned skills to build a full-featured application

**Project Ideas:**  
- Expense Tracker, Simple Game, File Manager, etc.

**Resources:**

- **Project Ideas:**  
  [GeeksforGeeks C Projects](https://www.geeksforgeeks.org/c-projects/)

**Practice Tasks:**
- Design and implement a project that interests you and leverages C++ concepts.

---

### Day 30: Review, Debugging, and Next Steps

**Topics Covered:**
- Reviewing all concepts
- Debugging techniques
- Exploring modern C++ enhancements (C++11, C++14, C++17, C++20)

**Resources:**

- **Reading:**  
  [LearnCpp.com – Introduction to Debugging](https://www.learncpp.com/cpp-tutorial/introduction-to-debugging/)  
  [What's New in C++11?](https://www.learncpp.com/cpp-tutorial/whats-new-in-cpp11/)  
  [CppCoreGuidelines](https://isocpp.github.io/CppCoreGuidelines)

**Practice Tasks:**
- Refactor your old code using modern C++ features.
- Identify and fix issues in some sample projects.

---

## Additional Tips for Success

- **Practice Daily:** Consistent coding is key.
- **Join Communities:**  
  - [Stack Overflow C++](https://stackoverflow.com/questions/tagged/c%2B%2B)  
  - [Reddit r/cpp](https://www.reddit.com/r/cpp/)
- **Read Open Source Code:** Explore projects on GitHub.
- **Ask Questions:** Use forums and communities whenever you're stuck.

---

Good luck on your journey to mastering C++! Enjoy the learning process, and remember to revisit topics if needed.

Happy Coding!
