SmartCampus Management System (Java Project)

📌 Problem Statement

This project is developed as part of the final assessment for BTech 2nd Year at GNC College.
The goal is to build a Smart Campus Management System that helps manage students, courses, and enrollments efficiently.

---

🎯 Objective

* Manage student and course data
* Allow students to enroll in multiple courses
* Handle invalid inputs using exception handling
* Process enrollments using multithreading
* Store and retrieve data using file handling

---

⚙️ Features

👨‍🎓 Student Management

* Add new students
* Store student details (ID, Name, Email)

📚 Course Management

* Add new courses
* Store course details (Course ID, Name, Fee)

📝 Enrollment System

* Enroll a student in one or more courses
* Uses "HashMap" and "ArrayList" for efficient storage

⚠️ Exception Handling

* Custom exception ("InvalidFeeException")
* Prevents invalid data like negative course fee

⚡ Multithreading

* Enrollment processing is done using threads
* Simulates real-time processing

💾 File Handling (Bonus)

* Save data to file ("data.ser")
* Load previously saved data

---

🛠️ Technologies Used

* Java (Core Java)
* OOP Concepts (Classes, Objects, Inheritance)
* Collections Framework
* Exception Handling
* Multithreading
* File Handling

---

▶️ How to Run

1. Compile the program:

javac SmartCampus.java

2. Run the program:

java SmartCampus

---

📷 Sample Output

* Menu-driven interface displayed in console
* User selects options to add students, courses, enrollments
* Thread message shows enrollment processing

---

📂 Project Structure

SmartCampus.java  
README.md  
data.ser (generated after saving data)  

---

🚀 Unique Feature Added

* Data persistence using file handling (Save & Load feature)

---

👨‍💻 Author

* Name: Nikhil Bhati
* Course: BTech (2nd Year)

---
