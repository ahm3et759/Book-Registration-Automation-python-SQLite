Sure! Here's a sample README section for the code you've shared:

---

# Book Registration System

This project is a **Book Registration System** developed using **Python**, **Tkinter** (for GUI), and **SQLite** (for database operations). The application allows users to add, list, and edit books in a database.

## Features

- **Add Books**: Users can add a new book by providing details like the book's title, author, publisher, page count, edition, and publication year.
- **List Books**: Displays all books stored in the database in a tabular format, allowing for easy viewing of all entries.
- **Search Function**: Users can search for books by title, author, or publisher.
- **Edit Books**: Books can be edited by selecting an entry, modifying the details, and saving the changes.
- **Delete Books**: Users can delete a book record from the database.

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- SQLite3 (comes bundled with Python)

## How to Run

1. Clone or download the repository.
2. Install any dependencies if necessary.
3. Run the Python file `book_registration_system.py`.

```bash
python book_registration_system.py
```

The application will launch, allowing you to add, view, search, edit, and delete books from the database.

## Database

The program uses **SQLite** to store book records in a local database file named `baglan.sql`.

### Table Structure

- **id** (INTEGER, PRIMARY KEY): Unique identifier for each book.
- **Kitap_Adi** (VARCHAR): The title of the book.
- **Yazar** (VARCHAR): The author of the book.
- **Yayin_Evi** (VARCHAR): The publisher of the book.
- **Sayfa_Sayisi** (INTEGER): The number of pages in the book.
- **Baski** (INTEGER): The edition number of the book.
- **Yayin_Yili** (INTEGER): The publication year of the book.

