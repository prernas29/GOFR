Clone this repository.

Create a .env file in the project's root directory and add the following:

MONGO_URI=mongodb://localhost:27017
PORT=8080

Run go run main.go in the project's root directory.

Endpoints

GET /books
Retrieve a list of all books.

GET /books/:id
Retrieve details of a specific book.

POST /books
Create a new book.

Input:

{
    "title": "Test Book",
    "author": "Me",
    "year": "2022"
}

PUT /books/:id
Update details of a book.

Input:

{
    "title": "Updated Book Title",
    "author": "Me",
    "year": "2022"
}
DELETE /books/:id
Delete a book.







