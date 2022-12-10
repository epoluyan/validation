Домашнее задание к занятию «2.5 Валидация и обработка ошибок. Interceptors, pipes»

1 задание.

Реализован interceptor MyInterceptor и подключен к методу findAll();

2 задание.

Реализован pipe ParseMongoIDPipe, который проверяет коррекность поля ID mongo. Подключен локально для валидации
параметра :id методов findOne(), deleteOne(), updateOne().

3 задание.

Реализована валидация входных данных с использованием библиотеки Joi и подключена локально для методов
create(), updateOne().

4 задание.

Создан Exception Filter HttpExceptionFilter и подключен в глобальной области видимости.