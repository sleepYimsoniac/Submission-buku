# bookshelf-hapi-api

#### # Run
By default, this API runs on endpoint `/books` and on port `9000`<br>
You can access it with `http://{url}:9000/books`

---
#### # Get All Books
* `'GET'`
* `http://{url}:9000/books`
<br>

#### # Get Book by ID
* `'GET'`
* `http://{url}:9000/books/{id}`
<br>

#### # Add Book
* `'POST'`
* `http://{url}:9000/books`
* `body`
<pre>{
    "name": "Buku Bacaan",
    "year": "2023",
    "author": "rifyan aditya",
    "summary": "dibaca agar bermanfaat",
    "publisher": "Gramed",
    "pageCount": "26",
    "readPage": "25",
    "reading": "false"
}</pre>
* `name` can't be an empty string
* `readpage` can't be larger than `pageCount`
<br>

#### # Edit Book by ID
* `'PUT'`
* `http://{url}:9000/books/{id}`
<br>

#### # Delete Book by ID
* `'DELETE'`
* `http://{url}:9000/books/{id}`
<br>

---

Educational purposes only
