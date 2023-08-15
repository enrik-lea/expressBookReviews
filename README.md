Final Project - Express Book Reviews
-
Postman use cases
-

Register user:
POST http://localhost:5000/register | {"username":"user1", "password":"password1"}

Login user:
POST http://localhost:5000/customer/login | {"username":"user1", "password":"password1"}

Get list of available books:
GET http://localhost:5000/

Get book info based on ISBN:
GET http://localhost:5000/isbn/3

Get book info based on Author:
GET http://localhost:5000/author/Unknown | GET http://localhost:5000/author/Dante Alighieri

Get book info based on Title:
GET http://localhost:5000/title/The Divine Comedy

Get book review by ISBN:
GET http://localhost:5000/review/3

Update book review:
PUT http://localhost:5000/customer/auth/review/3 | {"username":"user1", "review":"The book is great!!"}


Postman use cases with Promises:
-

Book list:
GET http://localhost:5000/promise/

Book info based on ISBN:
GET http://localhost:5000/promise/isbn/8

Info based on author:
GET http://localhost:5000/promise/author/Dante Alighieri

Info based on title:
GET http://localhost:5000/promise/title/The Divine Comedy

