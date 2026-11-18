📚 Library Management System

💻 Developed Using C Programming and Data Structures

📌 Project Overview

The Library Management System is a menu-driven console application developed using the C programming language to manage and maintain library book records efficiently.

The application uses a Singly Linked List for dynamic record management and file handling for data storage and retrieval. It follows a modular programming approach, with individual functionalities organized into separate header files for better code organization, readability, and maintainability.

 🎯 Key Features

- Add Book: Insert new book records.
- Display Books: View available book records.
- Search Book: Search for books using Book ID.
- Update Book: Modify existing book information.
- Remove Book: Delete selected book records.
- Save Records: Store book information using file handling.
- Read Records: Retrieve previously stored records.
- Main Menu: Navigate through different operations.

 🛠️ Technologies & Concepts

 Category - Implementation 

 Programming Language - C 
 Data Structure - Singly Linked List 
 Memory Management - Dynamic Memory Allocation 
 Data Storage - File Handling 
 Programming Approach - Modular Programming 
 Compiler - GCC 
 Platform - Windows 

 📂 Project Structure

text
Library-Management-System/

├── main.c
│
├── add.h
├── mainmenu.h
├── print.h
├── read.h
├── remove.h
├── save.h
├── search.h
├── struct.h
├── update.h
│
└── README.md

 ⚙️ Module Description

Header File - Responsibility 

`add.h` - Adds new book records. 
`mainmenu.h` - Manages the main menu. 
`print.h`  Displays book information. 
`read.h` - Reads saved records. 
`remove.h` - Deletes book records. 
`save.h` - Saves book information into a file. 
`search.h` - Searches for books using their ID. 
`struct.h` - Defines structures and linked list nodes. 
`update.h` - Updates existing book details. 

 🧠 Data Structure Implementation

 Singly Linked List

The application uses a Singly Linked List to maintain book records dynamically.

Each node contains:

- Book ID
- Book Name
- Author Name
- Pointer to the next node

This implementation supports dynamic insertion, deletion, and traversal of records.

 🚀 Compilation and Execution

Step 1: Open the project folder in your C development environment.

Step 2: Compile the source code using GCC.

gcc main.c -o library.exe

Step 3: Run the application.

library.exe

 📚 Learning Outcomes

- Practical implementation of linked lists.
- Understanding pointers and dynamic memory allocation.
- Modular programming using header files.
- File handling and data persistence.
- Implementation of insertion, deletion, searching, and updating operations.
- Applying data structures to real-world applications.

 🔮 Future Enhancements

- Book issue and return management.
- Library member registration.
- Book availability tracking.
- Fine calculation for overdue books.
- User authentication.

 👨‍💻 Developer

Venkatesh . R

Electronics and Communication Engineering

GitHub:https://github.com/rjvenkat15-lab/library-management-system

---

⭐ **Project Domain:** C Programming | Data Structures | File Handling | Application Development
