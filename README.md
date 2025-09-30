# Java Projects Collection

This repository contains three Java programs demonstrating key Java concepts: **autoboxing, object serialization, and file-based employee management**.

---

## 1. Sum Using Autoboxing

### Description
This program demonstrates **autoboxing and unboxing** in Java. Users can input integers, which are stored in an `ArrayList<Integer>`, and the program calculates the sum of all entered integers.

### Features
- Accept multiple integers as input.
- Uses autoboxing to store integers in an ArrayList.
- Calculates sum using unboxing.
- Input stops when user types `done`.

### File
- `SumUsingAutoboxing.java`

### How to Compile and Run
```bash
javac SumUsingAutoboxing.java
java SumUsingAutoboxing
2. Student Object Serialization
Description
This program demonstrates object serialization and deserialization in Java. A Student object is written to a file (student.ser) and then read back.

Features
Student class implements Serializable.

Serializes a Student object to student.ser.

Deserializes and prints the object to the console.

File
StudentSerialization.java

How to Compile and Run
bash
Copy code
javac StudentSerialization.java
java StudentSerialization
3. Employee Management System
Description
This is a menu-driven Employee Management System. It allows adding and displaying employee records. Employee objects are stored persistently using serialization.

Features
Add employee records: ID, Name, Designation, Salary.

Display all employees from employees.dat.

Supports appending objects without corrupting the file using AppendableObjectOutputStream.

Handles EOF and file-not-found errors gracefully.

Menu-driven console interface.

File
EmployeeManagementSystem.java

How to Compile and Run
bash
Copy code
javac EmployeeManagementSystem.java
java EmployeeManagementSystem
Dependencies
Java 8 or higher

No external libraries required
