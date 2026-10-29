# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small in-memory book catalog API with FastAPI. Practice defining data models, creating REST endpoints, and returning appropriate HTTP status codes.

## 📝 Tasks

### 🛠️ Create the API and Read Books

#### Description
Create a FastAPI application in `main.py` for managing books. Each book should have a unique integer ID, a title, and an author.

#### Requirements
Completed program should:

- Define a Pydantic model for book input with `title` and `author` fields, and store books in an in-memory collection.
- Provide `GET /books` to return all books and `GET /books/{book_id}` to return one book by ID.
- Provide `POST /books` to add a book, assign it a unique ID, and return the created book with a `201 Created` status.

### 🛠️ Update and Delete Books

#### Description
Add endpoints to update or remove a book, and handle requests for IDs that are not in the collection.

#### Requirements
Completed program should:

- Provide `PUT /books/{book_id}` to update a book's title and author.
- Provide `DELETE /books/{book_id}` to remove a book and return a `204 No Content` status.
- Return a `404 Not Found` response when a requested book ID does not exist, and verify the endpoints using FastAPI's `/docs` page.