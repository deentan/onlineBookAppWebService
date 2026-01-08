Routes
GET /allbooks
POST /addbook body: { book_name, book_author, book_img }
PUT /updatebook/:id params: { id }, body: { book_name, book_author, book_img }
DELETE /deletebook/:id params: { id }
