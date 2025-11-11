# QA-портфолио — \Алина Буцких

## 👋 Обо мне
Привет! Меня зовут **Алина**, я начинающий QA Manual engineer. 
Учусь и практикую в IT с **июля 2025 года**. Филологическое образование (с отличием, красный диплом). Специализация — отечественная лингвистика, анализ текста и языковых систем.
Люблю искать ошибки, улучшать процессы и превращать хаос в чёткую систему.  

---

## 🧰 Мои навыки и инструменты

**Типы тестирования:**
- Функциональное / Нефункциональное  
- UI / API тестирование  
- Smoke / Regression / Ad-hoc  
- Тестирование веб-приложений и клиент-серверных систем  

**Навыки:**
- Анализ требований  
- Составление тест-кейсов, чек-листов, баг-репортов  
- Работа с DevTools и Postman  
- Проверка запросов и ответов, работа с JSON  
- Написание SQL-запросов (SELECT, JOIN, WHERE, ORDER BY и др.)  

**Инструменты:**
- **Jira**, **Qase**, **TestIT**  
- **Postman**, **Chrome DevTools**  
- **PostgreSQL / MySQL**  
- **Git / GitHub**  

**Методологии:**
- Agile / Scrum / Kanban / Waterfall

---

## 🚀 Проекты

### Проект 1. DEMOQA — тестирование API и UI

**Описание:**  
Учебный проект по тестированию сайта [DEMOQA Book Store](https://demoqa.com/books).  
Проверка функционала авторизации, добавления книг, получения и удаления данных через API.  
Дополнительно протестированы UI-элементы и их соответствие ожидаемому поведению.

**Состав проекта 1:**
- 📋 **Чек-лист:** [https://docs.google.com/spreadsheets/d/1-8wOPv9jDyagjdeCUMK0pa_JNP9ZRmA0Vcp_pXQrtVs/edit?usp=sharing]
- 📄 **Тест-план:** [https://docs.google.com/document/d/1DCZT-mOCxqhMC47pamGK8wEW45sPLjdNG3skO8xG8qE/edit?usp=sharing]  
- 🧠 **Тест-кейсы и 🐞 Баг-репорты: (Jira):** [https://chuurippu.atlassian.net/jira/software/projects/PROJ/boards/35?atlOrigin=eyJpIjoiOGVhYWVhNzQyMDIxNDg1OWEzNzQ0OGZlOThmYWQxZjciLCJwIjoiaiJ9]

### Проект 2. SauceDemo — тестирование интернет-магазина

**Описание:**
Проект создан для демонстрации практических навыков ручного тестирования на примере сайта saucedemo.com
Проверялись ключевые функции интернет-магазина — авторизация, добавление и удаление товаров, работа корзины, оформление заказа и сортировка.

**Состав проекта 2:**
- 📋 **Чек-лист:** [https://docs.google.com/spreadsheets/d/1EVWE5csb731MQcnNdxo3z1SRdRUGecOhFG83a_U9M5Y/edit?usp=sharing]
- 📄 **Тест-план:** [https://docs.google.com/document/d/1s6bUuHxJp7zrxYWXO7FsdO2QpHJeVQvZAKFg-day5tE/edit?usp=sharing]
- 🧠 **Тест-кейсы и 🐞 Баг-репорты: (Jira):** [https://chuurippu.atlassian.net/jira/software/projects/PRJ/boards/68?atlOrigin=eyJpIjoiNWI0OGJjZDBiM2UzNGYxNWJiZTVlZDMzMDg0MTQ4ZjIiLCJwIjoiaiJ9]

---

## 🗄️ SQL & запросы

-- **Выбирает все значения таблицы "Books"**
SELECT * FROM Books;

-- **Выбирает заголовок и автора в книгах, содержащих более 300 страниц**
  SELECT Title, Author FROM Books WHERE Pages > 300;

-- **Выбирает пользователей, у которых в коллекции есть книги автора Robert C. Martin.**
SELECT 
    users.id,
    users.username,
    books.title,
    books.author
FROM 
    users
JOIN 
    user_books ON users.id = user_books.user_id
WHERE 
    books.author = 'Robert C. Martin';

---

## 📮 **Postman / API**

POST /Account/v1/User — 🤱 **создание пользователя**
<img width="1608" height="1018" alt="image" src="https://github.com/user-attachments/assets/cee30d71-d28b-436f-9c61-2d180a0567f5" />

POST /Account/v1/GenerateToken — 🔑 **генерация токена**
<img width="1603" height="1014" alt="image" src="https://github.com/user-attachments/assets/cbebe8e4-acf7-459c-b011-7bc8ead6663e" />

GET /BookStore/v1/Books — 📚 **список книг**
<img width="1606" height="1018" alt="image" src="https://github.com/user-attachments/assets/e9a4ea3f-0d19-458a-a307-46c3108f98ab" />

DELETE /BookStore/v1/Book — 🔥 **удаление несуществующей книги**
<img width="1608" height="1019" alt="image" src="https://github.com/user-attachments/assets/d70bf6c3-9c25-4e64-921c-3cbca9b53d75" />

---

## 📂 **DevTools**

❗ Ошибка 503 при вводе данных — страница "исчезает"
<img width="1918" height="876" alt="image" src="https://github.com/user-attachments/assets/71c677cb-2604-49c0-8d5b-791876dd0b1d" />

⚠ Некорректные запросы в Network при отправке формы авторизации
<img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/67bc363c-e3a8-463a-a3cc-f5fae9ef742f" />

✅ Успешное удаление товаров из корзины, ответ - 200
<img width="1919" height="875" alt="image" src="https://github.com/user-attachments/assets/7430d99e-feb0-4860-8ce2-3fc6542b39da" />

---

## 🤝 **Контакты**

* **Email:** \chuurippu@mail.ru
* **LinkedIn:** \[вставить позже]
* **Telegram:** @butskick

---

## 📜 **Лицензия**

<img width="842" height="596" alt="image" src="https://github.com/user-attachments/assets/0b011002-675c-42cf-b911-5768f2f9b12b" />
<img width="842" height="596" alt="image" src="https://github.com/user-attachments/assets/ad892bf7-3636-4e74-a4e0-9cd7cae92b67" />

