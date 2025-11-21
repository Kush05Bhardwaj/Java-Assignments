# Java Programming Assignment 3
## Student Record Management System – Exception Handling & Multithreading

**Name:** Kushagra Bhardwaj  
**Roll No.:** 2401010029  
**Course:** Java Programming  
**Programme:** B.Tech CSE Core  
**Session:** 2025-26  

---

### Project Description

This project is a console-based **Student Record Management System** implemented in Java.  
It demonstrates key programming concepts such as **custom exceptions**, **interfaces**, **multithreading**, and **input validation**.  
The application allows users to enter a student’s details, validates the input, displays a loading animation using threads, and finally shows the calculated grade.

---

### Objectives
- To implement a menu-based student record insertion system.
- To apply **custom exception handling** for missing student details.
- To demonstrate **multithreading** using the `Runnable` interface.
- To validate user input for roll number, marks, and text fields.
- To reinforce concepts like classes, objects, and interface implementation.

---

### Features
- **Custom Exception:** Throws `StudentNotFoundException` for empty or invalid fields.
- **Multithreading Loader:** Displays a loading animation using a separate thread.
- **Input Validation:**  
  - Roll number must be an integer.  
  - Name, email, and course cannot be empty.  
  - Marks must be between **0 and 100**.
- **Automatic Grade Calculation:**  
  - A → 90–100  
  - B → 75–89  
  - C → 60–74  
  - D → Below 60
- **Clean Output:** Shows a formatted student details report after processing.

---

### Technologies Used
- **Language:** Java  
- **Concepts Used:**  
  - Custom Exceptions  
  - Interfaces (`RecordActions`)  
  - Multithreading (`Thread`, `Runnable`)  
  - Exception Handling (`try-catch-finally`)  
  - Input Validation  
- **IDE/Editor:** VS Code / IntelliJ IDEA / Eclipse  
- **Execution Environment:** Java JDK 8 or above  
