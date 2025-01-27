# BookAPI
Basic REST API with Flask

        GET /books: Fetch all books.
        GET /books/<id>: Fetch a specific book by ID.
        POST /books: Add a new book (JSON body example: {"title": "Book Title", "author": "Author Name"}).
        PUT /books/<id>: Update an existing book (JSON body example: {"title": "Updated Title"}).
        DELETE /books/<id>: Delete a book.

git init
git add .
git commit -m "Initial commit: Basic REST API with Flask"
git branch -M main
git remote add origin https://github.com/Cyber-Netic/BookAPI/blob/main/app.py
git push -u origin main
