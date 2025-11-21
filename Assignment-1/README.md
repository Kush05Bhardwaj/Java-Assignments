# Java Programming Assignment 1
## Student Record Management – Inheritance & Grade Calculation

**Name:** Kushagra Bhardwaj  
**Roll No.:** 2401010029  
**Course:** Java Programming  
**Programme:** B.Tech CSE Core  
**Session:** 2025-26  

---

### Project Description

This project is a console-based **Student Record Management System** built using Java.  
It demonstrates the concepts of **inheritance**, **user-defined methods**, and **basic input validation**.  
The system allows users to enter multiple student details, automatically calculate grades, and display all stored records using a menu-driven interface.

---

### Objectives
- To implement **inheritance** using a parent `Person` class and a child `Student` class.
- To create a simple and interactive **menu-driven program**.
- To validate user input for marks and restrict values between **0 and 100**.
- To automatically calculate grades based on predefined criteria.
- To store multiple student records using `ArrayList`.

---

### Features
- **Inheritance Used:**  
  `Student` extends `Person`, reusing the `name` attribute.

- **User Input & Validation:**  
  The program validates marks and prompts again for invalid entries.

- **Automatic Grade Calculation:**  
  - A → 90 and above  
  - B → 75–89  
  - C → 60–74  
  - D → below 60  

- **Menu-Driven Interface:**  
  1. Add Student  
  2. Display All Students  
  3. Exit  

- **ArrayList-Based Storage:**  
  Dynamically stores multiple student objects without fixed size.

- **Clean, Formatted Output:**  
  Uses `displayDetails()` to print structured student information.

---

### Technologies Used
- **Language:** Java  
- **Concepts Applied:**  
  - Inheritance  
  - Encapsulation  
  - ArrayList Collections  
  - Conditional Logic  
  - Input Handling & Validation  
- **IDE/Editor:** VS Code / IntelliJ IDEA / Eclipse  
- **Execution Environment:** Java JDK 8 or above