# 📘 Student Record Management System
A simple Java console-based application designed to manage student records. This project demonstrates Object-Oriented Programming, methods, constructors, arrays/ArrayList, and control structures, as required in the assignment.

## 📌 Features

### ✔️Add Student
Allows the user to enter student details:

☞ Roll Number
☞ Name
☞ Course
☞ Marks
☞ Automatically calculates the student's grade based on the marks.

### ✔️Display All Students
Shows all student records in a clean, formatted view.

### ✔️Grade Calculation
Grades are assigned as per the following logic:

☞ A → Marks ≥ 90
☞ B → Marks ≥ 75
☞ C → Marks ≥ 60
☞ D → Marks < 60

## 🧰 Technologies Used

☞ Java (JDK 8 or above)
☞ OOP Concepts
☞ ArrayList for storing multiple records
☞ Scanner for user input
☞ Conditionals and Loops

## 📂 Project Structure

Student.java
MainApp.java

### Student.java
Contains the Student class with:

☞ Fields: rollNo, name, course, marks, grade

☞ Methods:

◦ inputDetails()
◦ displayDetails()
◦ calculateGrade()
◦ Constructors: default + parameterized

### MainApp.java
Contains:

◦ The main menu
◦ ArrayList for managing multiple students
◦ Logic for add/display/exit operations

## ▶️ How to Run the Program

1. Ensure Java JDK is installed
2. Save both files (Student.java and MainApp.java) in the same folder
3. Open a terminal or command prompt
4. Compile using:
    javac *.java
5. Run the application:
    java MainApp

## 📝 Sample Menu Output

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice:

## 🎯 Learning Outcomes

By completing this project, you will understand:

☞ Class and object creation
☞ Method implementation
☞ Constructors in Java
☞ ArrayList usage
☞ User input and menu-driven applications
☞ Grade calculation using conditional logic

