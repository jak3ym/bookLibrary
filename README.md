# Book Library API

This is a simple Book Library API built with FastAPI. It allows you to manage a collection of books, including creating, reading, updating, and deleting books.

## Features

- **Get all books**: Retrieve a list of all books in the library.
- **Get a specific book**: Retrieve details of a specific book by its ID.
- **Add a new book**: Add a new book to the library.
- **Update a book**: Update the details of an existing book.
- **Delete a book**: Remove a book from the library.

## Requirements

- Python 3.7+
- FastAPI
- Uvicorn

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/your-username/bookLibrary.git
   cd bookLibrary
  ```
## Dependencies
  - uvicorn
  ```bash
  pip install fastapi uvicorn
  ```
## Run the server
  Run the instance:
  ```bash
  uvicorn main:app --reload
  ```
  - Access the book list: http://127.0.0.1:8000
  - Access the UI (Swagger UI): http://127.0.0.1:8000/docs
