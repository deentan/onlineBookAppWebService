Routes <br>
GET /allbooks <br>
POST /addbook body: { book_name, book_author, book_img } <br>
PUT /updatebook/:id params: { id }, body: { book_name, book_author, book_img } <br>
DELETE /deletebook/:id params: { id }
