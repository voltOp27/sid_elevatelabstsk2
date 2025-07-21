Student Record Management System
Overview
This project is a CLI-based CRUD application for managing student records, designed for the Elevate Labs Java Developer Internship assignment. It demonstrates the use of Java, object-oriented programming, encapsulation, and Java Collections (ArrayList). The system enables users to easily add, view, update, and delete student records via a menu-driven console interface.

Features
Add Student: Input student ID, name, and marks to add a new record.

View All Students: Display a list of all saved student records.

Update Student: Modify details of an existing student using their ID.

Delete Student: Remove a student record by entering their ID.

Encapsulation: Student details are managed with private fields and public getters/setters.

ArrayList Storage: Dynamically manage records without fixed limits.

Prerequisites
Java JDK (version 8 or above)

VS Code (or IntelliJ IDEA Community Edition)

Java Extension Pack (for VS Code)

Setup and Running
Clone the repository (or download the files to a folder).

Ensure files Student.java and StudentManager.java are in the same directory.

Open the folder in VS Code.

Compile the Java files:

text
javac Student.java StudentManager.java
Run the application:

text
java StudentManager
Use the CLI menu to interact with the student records.

Project Structure
File	Purpose
Student.java	Defines the Student data model
StudentManager.java	Main logic and CLI for records
Key Concepts Practiced
Classes & Objects

Encapsulation

Java Collections (ArrayList)

Loops and Menu-Driven Programs

Example
Sample menu on execution:

text
--- Student Record Management System ---
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit
