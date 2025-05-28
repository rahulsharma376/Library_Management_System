📚 Library Management System
This is a console-based Library Management System developed in C. It enables users to manage book records effectively, including functionalities for adding, deleting, editing, searching, and viewing books. It also includes admin login and password management for restricted access.

🛠️ Features
Admin authentication with Sign Up / Sign In

Add new books with category, author, and pricing details

Delete book records by ID

Edit book information (name, author, quantity, price, rack number)

Search for books by ID or name

View all book records in a formatted list

Password change functionality

Persistent storage using binary files (Record.dat and password.dat)

📁 File Structure
Library_Management.c: Main source file

general_functions.h, core_functions.h: Header files (assumed to contain declarations for UI and file handling functions)

Record.dat: Binary file to store book records

password.dat: Binary file to store admin credentials

🧱 Technologies Used
Language: C

Concepts: File handling, structures, console-based UI, modular programming

▶️ How to Run
Compile the code using a C compiler:

bash
Copy
Edit
gcc Library_Management.c -o LibraryManagement
Run the executable:

bash
Copy
Edit
./LibraryManagement
If no password.dat is found, the program will prompt you to sign up as an admin.

📝 Functional Overview
Main Menu Options:

Add Books

Delete Book

Search Book

View Book List

Edit Book Record

Change Password

Close Application

Data Fields for Each Book:

Category

ID

Name

Author

Quantity

Price

Rack Number

✅ Future Improvements
Add book issue/return functionality

Implement student/member records

Improve UI with a GUI framework

Encrypt passwords for better security

📌 Note
Ensure the program runs in a terminal or environment that supports gotoxy() and Windows-specific headers like <conio.h> and <windows.h>, or refactor for cross-platform compatibility.
