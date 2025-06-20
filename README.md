# Student Management System

This is a simple **Student Management System** implemented in Python using Object-Oriented Programming (OOP) concepts. The system manages undergraduate and postgraduate student information, supporting add, search, and display operations.

---

## Features

- Add Undergraduate Student (Name, Roll No, Branch)
- Add Postgraduate Student (Name, Roll No, Branch, Thesis Topic)
- View all students
- Search student by roll number

---

## Classes

- `Person`  
  Base class representing a person with a name.

- `Student` (inherits from `Person`)  
  Represents an undergraduate student with roll number and branch.

- `PGStudent` (inherits from `Student`)  
  Represents a postgraduate student with an additional thesis topic attribute.

- `StudentManager`  
  Manages a list of students and provides methods to add and search students.

- `App`  
  Main application class with a command-line menu interface for interacting with the system.

---

## How to Run

1. Clone the repository or download the code.
2. Make sure you have Python installed (version 3.x recommended).
3. Run the script using:

   python StudentManagmentSystem.py

## Sample Usage

After running the script (`StudentManagmentSystem.py`), you will see a menu like this:

===== Student Management System =====
1. Add Student
2. Add PostGraduate Student
3. View All Students
4. Search Student by Roll No
5. Exit
Enter choice: 1
Enter name: John Doe
Enter roll no: 101
Enter branch: Computer Science
Student added.

===== Student Management System =====
Enter choice: 3
Student: John Doe, Roll No: 101, Branch: Computer Science





