# Inventory Management Application 📚

A simple command-line **Library Book Tracker** application built in C++. This project lets users add, view, search, and remove books from a collection stored in a file.

---

## ✨ Features

- Add new books with title, author, and ISBN
- View all books in the library
- Search for books by title or author
- Remove books from the collection
- Persistent storage using a text file (`books.txt`)

---

## 📁 Project Structure

```
LibraryBookTracker/
├── src/
│ ├── main.cpp # Application entry point & menu logic
│ ├── Book.h # Book class definition
│ ├── Book.cpp # Book class implementation
│ ├── LibraryManager.h # Library management class definition
│ ├── LibraryManager.cpp # Library management implementation
│ └── utils.h # (Optional) Helper functions
├── data/
│ └── books.txt # Stored book records
├── README.md
└── LICENSE (optional)
```

