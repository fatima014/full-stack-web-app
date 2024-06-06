# full stack web app

## Description

This is a web application designed to manage authors and their books. It provides functionalities to create, read, update, and delete both authors and books. The application is built using Node.js and Express, and it utilizes MongoDB for database operations. The frontend is rendered using EJS templates.

## Features

### Authors

- **List all authors**: View a list of all authors in the database.
- **Search authors**: Search for authors by name.
- **Add new author**: Create a new author entry.
- **View author details**: View detailed information about an author, including a list of books written by them.
- **Edit author**: Update an author's information.
- **Delete author**: Remove an author from the database.

### Books

- **List all books**: View a list of all books in the database.
- **Search books**: Search for books by title and publication date.
- **Add new book**: Create a new book entry, including details like title, author, publication date, page count, and a description.
- **View book details**: View detailed information about a book.
- **Edit book**: Update a book's information.
- **Delete book**: Remove a book from the database.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/fatima014/full-stack-web-app.git
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up MongoDB**:
    Ensure MongoDB is installed and running on your local machine or provide a MongoDB Atlas URI in the environment variables.

4. **Create environment variables**:
    Create a `.env` file in the root directory and add your MongoDB URI:
    ```
    DATABASE_URL=<your-mongodb-uri>
    ```

5. **Run the application**:
    ```bash
    npm start
    ```

6. **Access the application**:
    Open your browser and go to `http://localhost:3000`.

## Usage

### Authors

- **List authors**: Navigate to `/authors` to see all authors.
- **Add a new author**: Go to `/authors/new`, fill out the form, and submit.
- **View author details**: Click on an author's name in the list to see detailed information.
- **Edit an author**: On the author's detail page, click the "Edit" button.
- **Delete an author**: On the author's detail page, click the "Delete" button.

### Books

- **List books**: Navigate to `/books` to see all books.
- **Add a new book**: Go to `/books/new`, fill out the form, and submit.
- **View book details**: Click on a book's title in the list to see detailed information.
- **Edit a book**: On the book's detail page, click the "Edit" button.
- **Delete a book**: On the book's detail page, click the "Delete" button.

