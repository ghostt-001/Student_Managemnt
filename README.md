# 📘 Student Management System - Java (Console-Based)

## 🧾 Description
This is a **console-based Student Management System** implemented in Java. It uses **Object-Oriented Programming (OOP)** principles such as **inheritance, method overloading, method overriding, and constructor overloading**.

The program allows the user to:
- Add student records
- Display all stored student information
- Calculate grades using either overall marks or a combination of theory and practical marks

## 🛠️ Features
- Add multiple student records (up to 100)
- Display complete student details
- Grade calculation using:
  - Total marks
  - Separate theory and practical marks
- Menu-driven interface
- Demonstrates key OOP concepts

## 👨‍🏫 OOP Concepts Demonstrated

| Concept              | Description |
|----------------------|-------------|
| **Inheritance**      | `Student` inherits from `Person` |
| **Method Overriding**| `displayInfo()` is overridden in `Student` |
| **Method Overloading**| `calculateGrade()` is overloaded to support different inputs |
| **Constructor Overloading** | Both classes have default and parameterized constructors |

## 🔍 How It Works

1. **Add Student**  
   Inputs: Name, Age, Roll Number, Marks  
   → Creates and stores a new `Student` object.

2. **Display Students**  
   → Lists all students with name, age, roll number, marks, and grade.

3. **Calculate Grade (Theory & Practical)**  
   Inputs: Theory Marks, Practical Marks  
   → Calculates average and displays grade using overloading.

4. **Exit**  
   → Closes the program.

## 🖥️ Code Structure
class Person    
 └── name, age    
 └── displayInfo()    

class Student extends Person    
 └── rollNo, marks   
 └── calculateGrade(double)    
 └── calculateGrade(int, int)    
 └── displayInfo() [overridden]    

public class StudentManagement    
 └── main() method with menu logic    

## ✅ Requirements
Java JDK 8 or later

Any Java IDE (like IntelliJ, Eclipse, or VS Code) or command line

## 📁 File
CODE — Contains all class definitions and the main driver logic.


