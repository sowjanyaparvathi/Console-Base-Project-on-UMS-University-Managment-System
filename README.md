# Console-Base-Project-on-UMS-University-Managment-System
This is a command-line based College Management System written in Python. It allows users to manage multiple colleges, along with their students and teachers. The system uses object-oriented programming concepts like inheritance, encapsulation, and polymorphism to manage and organize data efficiently.

🔧 Features
✅ Create and manage multiple colleges

👨‍🎓 Add and view students

👩‍🏫 Add and view teachers

🔍 Search students and teachers by their roll numbers

🧾 Simple, text-based menu interface

🛑 Error handling for invalid inputs and non-existent colleges

🧱 Object-Oriented Structure
Person (Base class): Contains common attributes like rollno and name.

Student (Inherits from Person): Adds a branch attribute.

Teacher (Inherits from Person): Adds a subject attribute.

College: Stores a list of students and teachers, and provides methods to add, search, and display them.

📋 Menu Options
Create College

Add Student

Add Teacher

Display Students

Display Teachers

Search Student by Roll Number

Search Teacher by Roll Number

Exit Program

🛠 How It Works
Users interact with the program through a menu-driven interface.

Each college is managed independently, allowing for the addition of its own students and teachers.

Student and teacher searches are performed within the context of a selected college.

Input validation ensures smooth user experience.

📌 Requirements
Python 3.x

No external libraries required

🚀 How to Run
Save the Python script to a .py file (e.g., college_management.py)

Open a terminal or command prompt.

Run the script:

bash
Copy
Edit
python college_management.py
📈 Future Enhancements (Optional)
Save/load data to/from files (e.g., using JSON or pickle)

Add update/delete features for students and teachers

GUI or web-based interface

Prevent duplicate roll numbers

Case-insensitive name matching


