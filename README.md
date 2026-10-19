# Library Management System (Java)

A console-based Library Management System built with core Java and OOP concepts.

## Features
- Add books and members
- Issue and return books (3-book limit, 14-day loan period)
- Automatic fine calculation for late returns (2.00 per day)
- Search books by title or author
- List all books and members

## Requirements
- Java JDK 14 or newer

## How to Run
```
javac LibraryManagementSystem.java
java LibraryManagementSystem
```

## Menu Options
| Option | Action |
|--------|--------|
| 1 | Add book |
| 2 | Add member |
| 3 | Issue book |
| 4 | Return book |
| 5 | Search books |
| 6 | List all books |
| 7 | List all members |
| 0 | Exit |

## Project Structure
```
LibraryManagementSystem.java   # Book, Loan, Member, Library and main menu
README.md
.gitignore
```

## Future Scope
- Database storage (MySQL / SQLite using JDBC)
- GUI using Swing or JavaFX
- Login for admin and members
- Web version using Spring Boot
