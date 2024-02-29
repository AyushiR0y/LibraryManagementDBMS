
# Library-Management-System

**Project Title:** Library Management System

**Scope and Objectives:**

The Library Management System is designed to streamline library operations efficiently. It offers a user-friendly interface for librarians to manage various tasks seamlessly, including:

- **User Authentication:** Librarians can securely log in using their unique username and password to access the system.

- **Functionality:** Once logged in, librarians can perform essential functions such as adding new books, registering new students, issuing books, accepting returns, and accessing transaction statistics.

- **Book Management:** Each book in the system is identified by its ISBN number and includes details like title, author, price, and quantity.

- **Student Management:** The system maintains records for each student, including student ID, name, course, branch, and year.

- **Book Issuance:** Librarians can issue books to students by entering the book's ISBN number, the student's ID, and the issue date.

- **Return Process:** When a student returns a book, the librarian records the student's ID, specifies the return date, and updates the book's status to "returned" or "available."

**Database Structure:**

The project utilizes PostgreSQL for database management, consisting of four essential tables:

- **Book Table:** Contains fields for ISBN, title, author, price, and quantity.
- **Admin Table:** Stores login credentials for administrators.
- **Student Table:** Holds student information such as ID, name, course, branch, and email.
- **Record Table:** Tracks book issuance and return records, including student ID, ISBN, issue date, and return date.
![WhatsApp Image 2024-02-28 at 8 58 46 AM](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/f8d3b6a4-166c-455a-8e49-7e3228350ae5)
![WhatsApp Image 2024-02-28 at 8 58 21 AM (1)](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/2118fbf8-c863-40bf-acd9-95a2889ee066)
![WhatsApp Image 2024-02-28 at 8 58 21 AM](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/3d4f25d4-3b36-42d2-a155-d3f0692d2607)
![WhatsApp Image 2024-02-28 at 8 57 38 AM](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/126fb38e-b824-41f5-af90-04048367cbe3)
![WhatsApp Image 2024-02-28 at 8 57 23 AM](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/cd4ecc9f-96f4-46b3-8c3f-d6845a90a22a)
![WhatsApp Image 2024-02-28 at 8 56 49 AM](https://github.com/AyushiR0y/LibraryManagementDBMS/assets/132144705/b43cb684-b130-489b-a86d-a9ba1b23ff4e)







