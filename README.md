### Домашняя работа к лекции «Работа с PostgreSQL из Python»

[задание](https://github.com/netology-code/py-homeworks-db/tree/video/05-psycopg)

------
Согласно заданию создана программа для управления клиентами на python.

Хранится персональная информация о клиентах:

- имя
- фамилия
- email
- телефон
у клиента может быть не один, а два, три и даже больше. 
А может и вообще не быть телефона (например, он не захотел его оставлять).

Разработана структура БД для хранения информации и несколько функций на python для управления данными:

- Функция, создающая структуру БД (таблицы)
- Функция, позволяющая добавить нового клиента
- Функция, позволяющая добавить телефон для существующего клиента
- Функция, позволяющая изменить данные о клиенте
- Функция, позволяющая удалить телефон для существующего клиента
- Функция, позволяющая удалить существующего клиента
- Функция, позволяющая найти клиента по его данным (имени, фамилии, email-у или телефону)