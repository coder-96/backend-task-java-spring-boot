# RESTFUL todolist

## Table of contents

- [Задачи](#overview)
- [Общие требования](#the-challenge)
- [Создано с помощью](#built-with)
- [Инструкция использования API](#instructions)
- [Полезные ресурсы](#usefulres)
- [Автор](#author)

## Overview

- Задача 1: Создание RESTful API
- Задача 2: Интеграция с базой данных
- Задача 3: Обработка ошибок
- Задача 4: Документация API
- Задача 5: Тестирование



### Общие требования

- Используйте Java и Spring Boot для разработки.
- Используйте Maven или Gradle для управления зависимостями.
- Код должен быть хорошо структурирован и читаем.
- Используйте принципы RESTful дизайна API.
- Добавьте комментарии там, где это необходимо.
- Включите инструкции по развертыванию и запуску приложения.

### Создано с помощью

- Java
- Maven

### Инструкция использования API

Запросы к API
Чтобы отправить запрос к API, можно использовать POSTMAN или другой альтернатив.

Получение информации о всех задачах
GET http://localhost:8080/api/todos

Добавление новой задачи
POST http://localhost:8080/api/todos

Пример заполнения JSON:
{
    "title": "Купить продукты",
    "completed": false
}

Инфо об одной определенной задаче
GET http://localhost:8080/api/todos/{id}

Обновление информации о задаче
PUT http://localhost:8080/api/todos/{id}

Удаление задачи
DELETE http://localhost:8080/api/todos/{id}

### Полезные ресурсы

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - искал информацию когда застрявал.

## Автор

- Website - [Jalga](https://github.com/coder-96)
