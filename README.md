## Sprint 13

# A MongoDB project

# Javascript, Node.js, express, Mongo.db


* в .eslintrc добавлено исключение для _id;
* Node.js приложение подключается к серверу Mongo по адресу mongodb://localhost:27017/mestodb;
* создана схема и модель пользователя с полями name, about и avatar, поля корректно валидируются;
* создана схема и модель карточки с полями name, link, owner, likes и createdAt, поля корректно валидируются;
* запрос на GET /users возвращает всех пользователей из базы;
* запрос GET /users/:userId возвращает конкретного пользователя;
* запрос POST /users создаёт пользователя;
* запрос GET /cards возвращает все карточки всех пользователей;
* запрос POST /cards создаёт карточку;
* папки public и data удалены;
