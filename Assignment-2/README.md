# Java Programming Assignment 2
## Student Management System – Abstraction, Interfaces & CRUD Operations

**Name:** Kushagra Bhardwaj  
**Roll No.:** 2401010029  
**Course:** Java Programming  
**Programme:** B.Tech CSE Core  
**Session:** 2025-26  

---

### Project Description

This project is a console-based **Student Management System** created using Java.  
It demonstrates **abstraction**, **interfaces**, **method overloading**, and **CRUD operations** (Create, Read, Update, Delete).  
The system allows users to add, update, delete, search, and view student records using a HashMap-based storage system for fast lookups.

---

### Objectives
- To implement **abstraction** using an abstract `Person` class.
- To demonstrate **method overloading** with two `calculateGrade()` methods.
- To implement **interfaces** for record management using the `RecordActions` interface.
- To perform **CRUD operations** on student data.
- To use **HashMap** for efficient student record storage and retrieval.
- To follow clean object-oriented design using classes, inheritance, and overriding.

---

### Features

- **Abstraction using Abstract Class:**  
  `Person` is an abstract class storing name and email, with an abstract method `displayInfo()`.

- **Student Class (Inheritance + Overloading):**  
  - Inherits from `Person`.  
  - Includes overloaded methods:  
    - `calculateGrade(double marks)`  
    - `calculateGrade(int marks)`  
  - Automatically assigns grade based on marks.

- **Interface-based Design:**  
  `RecordActions` defines required functions:  
  - `addStudent()`  
  - `deleteStudent()`  
  - `updateStudent()`  
  - `searchStudent()`  
  - `viewAllStudents()`  

- **HashMap for Data Storage:**  
  Stores students with roll number as key for O(1) operations.

- **Full CRUD Functionality:**  
  - Add Student  
  - View All Students  
  - Search Student  
  - Update Student  
  - Delete Student  
  - Exit  

- **Menu-Driven Interface:**  
  User-friendly console menu for seamless navigation.

---

### Technologies Used
- **Language:** Java  
- **OOP Concepts Implemented:**  
  - Abstraction  
  - Inheritance  
  - Interfaces  
  - Method Overloading  
  - Polymorphism  
  - Encapsulation  
- **Collections Used:** `HashMap`  
- **IDE/Editor:** VS Code / IntelliJ IDEA / Eclipse  
- **Execution Environment:** Java JDK 8 or above
