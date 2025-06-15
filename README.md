# Bookshelf API

A simple RESTful API for managing a collection of books, built with Node.js and Hapi.js.

## Features

- Add a new book
- Get all books
- Get book details by ID
- Edit book details
- Delete a book

## Requirements

- Node.js (v14 or higher)
- npm

## Installation

1. Clone the repository:
```bash
git clone https://github.com/alfrdzley/Submission-Bookshelf-API/
```
2. Install Dependencies
```bash
npm install
```
3. Run the server
```bash
npm run start-dev
```

The server will run on `http://localhost:9000`.

## API Endpoints

### Add a Book

- **POST** `/books`
- Request body:  
  ```json
  {
    "name": "Book Name",
    "year": 2021,
    "author": "Author Name",
    "summary": "Book summary",
    "publisher": "Publisher Name",
    "pageCount": 100,
    "readPage": 10,
    "reading": false
  }

### Get a Book

- **GET** `/books`
- **GET** `/books/{bookId}`
- **PUT** `/books/{bookId}`
- **DELETE** `/books/{bookId}`
