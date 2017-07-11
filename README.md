This is a simple falsk based rest endpoint provider. Following the end points that are available in this.

get all the books available
Method: GET
Endpoint: /library/v1.0/books

get a particulare book. isbn is a int here.
Method: GET
Endpoint: /library/v1.0/books/<isbn>

add a book to library
Method: POST
Endpoint: /library/v1.0/books

Update the details of a book
Method: PUT
Endpoint: /library/v1.0/books/<int:isbn>

Remove a book from library
Method: DELETE
Endpoint: /library/v1.0/books/<int:isbn>

this is a new_branch
