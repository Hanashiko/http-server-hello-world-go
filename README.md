
# 👋 HTTP Server Hello World (Go)

Цей проєкт — простий HTTP-сервер на Go, який повертає повідомлення "Hello, [name]". Це класичний приклад "Hello, World!" із підтримкою query-параметрів.

## 🧠 Опис

Сервер обробляє HTTP GET-запити на маршрут `/hello`, читає параметр `name` з URL, і повертає вітальне повідомлення типу `Hello John`.

## 🚀 Запуск

1. Скопіюйте репозиторій

2. Запусти сервер:

```bash
go run main.go
```

3. Зроби HTTP-запит:

```bash
curl "http://localhost:8000/hello?name=World"
# Output: Hello World

curl "http://localhost:8000/hello?name=Oksana"
# Output: Hello Oksana
```

##📌 Примітки

- Якщо name не вказано — результатом буде Hello (з пробілом).

- Код підходить для ознайомлення з основами роботи з HTTP у Go.
