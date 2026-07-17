# contact-manager-python
Contact Manager System (Python)

📌 Project Overview

The Contact Manager System is a command-line application developed using Python that allows users to manage their personal or professional contacts efficiently. The application provides essential contact management features such as adding new contacts, displaying all saved contacts, updating existing contact information, and deleting contacts whenever required.

This project demonstrates the practical implementation of Object-Oriented Programming (OOP) concepts in Python, including classes, objects, inheritance, constructors, and methods. It also showcases the use of Python lists for data storage, user input handling, loops, conditional statements, and exception handling.

Although this project stores data temporarily in memory (without using a database or file storage), it serves as an excellent beginner-level application for understanding CRUD (Create, Read, Update, Delete) operations and object-oriented design.

---

🎯 Objectives

- Build a simple command-line Contact Management application.
- Practice Python Object-Oriented Programming concepts.
- Implement CRUD operations on contact records.
- Learn how to organize code using classes and methods.
- Improve problem-solving and programming logic.

---

✨ Features

- ➕ Add new contacts.
- 👀 Display all saved contacts.
- ✏️ Update an existing contact's mobile number or email address.
- ❌ Delete unwanted contacts.
- 🚫 Prevent duplicate contact names.
- ⚠️ Basic exception handling for invalid user input.
- 📋 Easy-to-use menu-driven interface.

---

🛠 Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- Command Line Interface (CLI)

---

📂 Project Structure

contact-manager-python/
│
├── contact_project.py
└── README.md

---

📖 Functionalities

1. Add Contact

Users can create a new contact by entering:

- Name
- Mobile Number
- Email Address

Before adding the contact, the application checks whether a contact with the same name already exists. If a duplicate is found, the application displays an appropriate message and prevents duplication.

---

2. Display Contacts

Displays all available contacts in a clean and readable format showing:

- Name
- Phone Number
- Email Address

Each contact is displayed separately for better readability.

---

3. Update Contact

Users can update an existing contact by searching with the contact name.

Available update options:

- Update Mobile Number
- Update Email Address

Only the selected field is modified while the remaining information stays unchanged.

---

4. Delete Contact

Users can remove any contact by entering the contact name.

Once found, the contact is removed from the contact list.

---

🏗 Object-Oriented Design

The project contains two classes:

Contact

Responsible for storing individual contact information.

Attributes:

- Name
- Mobile Number
- Email Address

Methods:

- Display Contact Details

---

Contact_Manager

Responsible for managing all contacts.

Methods include:

- Add Contact
- Display Contacts
- Update Contact
- Delete Contact

---

▶️ How to Run

1. Install Python 3.
2. Download or clone this repository.
3. Open the project folder.
4. Run the program using:

python contact_project.py

5. Select the desired option from the menu.

---

📸 Sample Menu

Choose the following operation:

1. Add Contact
2. Display Contacts
3. Update Contact
4. Delete Contact
5. Exit

---

📚 Concepts Covered

- Classes and Objects
- Inheritance
- Constructors
- Methods
- Lists
- Loops
- Conditional Statements
- Functions
- Exception Handling
- User Input
- CRUD Operations

---

🚀 Future Improvements

This project can be enhanced by adding:

- File storage using CSV or JSON
- SQLite or MySQL database integration
- Contact search functionality
- Contact sorting
- Contact groups/categories
- Password protection
- Graphical User Interface (GUI) using Tkinter or PyQt
- Export contacts to CSV or Excel
- Import contacts from external files
- Contact backup and restore
- Profile pictures for contacts

---

🎓 Learning Outcomes

After completing this project, you will gain practical knowledge of:

- Python programming fundamentals
- Object-Oriented Programming
- CRUD application development
- Data management using lists
- User interaction through the command line
- Writing modular and reusable Python code

---

📄 License

This project is created for educational and learning purposes. You are free to modify, improve, and use it for personal practice.

---

👨‍💻 Author

Developed using Python as a beginner-friendly project to understand Contact Management Systems and Object-Oriented Programming concepts.
