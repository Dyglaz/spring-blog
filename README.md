# Spring Blog Application

## About the Project

This web application is designed for managing a blog, developed using the Spring Framework and Thymeleaf. The application allows users to perform CRUD (Create, Read, Update, Delete) operations for blog posts, including their title, announcement, full text, and views.

## Key Features

- **View Blog Posts**: Display all blog posts stored in the database.
- **Add New Post**: A form for entering data for a new blog post.
- **Edit Post**: Ability to edit existing blog posts.
- **Delete Post**: Remove blog posts from the database.

## Technologies

- **Spring MVC:** For creating web applications and handling HTTP requests.
- **Spring Data JPA:** For interacting with the MySQL database.
- **Thymeleaf:** A templating engine for dynamically generating HTML pages.
- **Bootstrap:** For styling and responsive design of the interface.
- **Lombok:** To reduce boilerplate code in models.

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/spring-blog.git
   cd spring-blog
   ```

2. **Set up the database**:
    - Ensure that MySQL is installed.
    - Create a database named `spring_web_blog`:
      ```sql
      CREATE DATABASE spring_web_blog;
      ```

3. **Configure connection parameters**:
    - Open the `application.properties` file and modify the database connection parameters (URL, username, password):
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/spring_web_blog
      spring.datasource.username=root
      spring.datasource.password=admin
      ```

4. **Run the application**:
    - Use your IDE or command line to run the application.

## Usage

- Navigate to `http://localhost:8080/blog` to access the blog application.
- Use the interface to add, edit, and delete blog posts.


---


# Приложение для блога на Spring

## О проекте
Это веб-приложение предназначено для управления блогом и разработано с использованием Spring Framework и Thymeleaf. Приложение позволяет пользователям выполнять операции CRUD (создание, чтение, обновление и удаление) для записей блога, включая их название, анонс, полный текст и количество просмотров.

## Основные функции
- **Просмотр записей блога:** Отображение всех записей блога, сохраненных в базе данных.
- **Добавление новой записи:** Форма для ввода данных новой записи блога.
- **Редактирование записи:** Возможность редактировать существующие записи блога.
- **Удаление записи:** Удаление записей блога из базы данных.

## Технологии
- **Spring MVC:** Для создания веб-приложения и обработки HTTP-запросов.
- **Spring Data JPA:** Для взаимодействия с базой данных MySQL.
- **Thymeleaf:** Шаблонизатор для динамической генерации HTML-страниц.
- **Bootstrap:** Для стилизации и адаптивного дизайна интерфейса.
- **Lombok:** Для уменьшения объема шаблонного кода в моделях.

## Установка и настройка

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/yourusername/spring-blog.git
   cd spring-blog
    ```
   
2. **Настройте базу данных**:
    - Убедитесь, что у вас установлен MySQL.
    - Создайте базу данных с именем `spring_web_blog`:
      ```sql
      CREATE DATABASE spring_web_blog;
      ```

3. **Настройте параметры подключения**:
    - Откройте файл application.properties и измените параметры подключения к базе данных (URL, имя пользователя, пароль):
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/spring_web_blog
      spring.datasource.username=root
      spring.datasource.password=admin
      ```

4. **Запустите приложение**:
    - Используйте вашу IDE или командную строку для запуска приложения.

## Использование

- Перейдите по адресу http://localhost:8080/blog для доступа к блогу.
- Используйте интерфейс для добавления, редактирования и удаления записей блога.
