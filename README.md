# Library Management System

![Screenshot 2024-06-02 131825](https://github.com/iKoNFlair/Library-Management-System/assets/102801379/d5ea6ee0-9fad-479f-8702-d93fdae7f37d)
![Screenshot 2024-06-02 132102](https://github.com/iKoNFlair/Library-Management-System/assets/102801379/18831fab-066e-41d1-bc49-f4ee4565a47a)

## Overview

This Library Management System is a console-based application written in C++. It utilizes file handling to manage and store data about students, books, book issues, and deposits. The system is designed to help libraries keep track of their books and the students who borrow them.

## Features

- **Student Management**: Add, update, view, and delete student records.
- **Book Management**: Add, update, view, and delete book records.
- **Book Issue**: Issue books to students and keep track of issued books.
- **Book Deposit**: Record the return of issued books and update records accordingly.
- **File Handling**: All data is stored in files to ensure persistence between program runs.

## Getting Started

### Prerequisites

- TurboC++ compiler

### Main Menu

1. **Student Management**
   - Add Student
   - View Students
   - Update Student
   - Delete Student

2. **Book Management**
   - Add Book
   - View Books
   - Update Book
   - Delete Book

3. **Issue Book**
   - Issue a book to a student

4. **Deposit Book**
   - Record the return of a book

### Sample Workflow

1. **Add a Student**: Enter the student's details including name, ID, and contact information.
2. **Add a Book**: Enter the book's details including title, author, and ISBN.
3. **Issue a Book**: Select a student and a book to issue.
4. **Deposit a Book**: Select the issued book to mark it as returned.

## File Structure

- **students.dat**: Contains all student records.
- **books.dat**: Contains all book records.
