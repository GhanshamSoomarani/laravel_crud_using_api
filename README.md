<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="380" alt="Laravel Logo">
  </a>
  <span style="margin: 0 20px;"></span>
  <a href="https://postman.com" target="_blank">
    <img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/postman-icon.svg" width="80" alt="Postman Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>


---

# 📌 Laravel Task Manager API

A simple **RESTful API** built with **Laravel** for managing tasks. This API supports CRUD operations and is tested using **Postman**. It use **MySQL** for data storage.


---

## 📋 Table of Contents

- [Features](#-features)
- [Tools & Technologies](#-tools--technologies)
- [Getting Started](#-getting-started)
- [API Endpoints](#-api-endpoints)
- [Postman Testing](#-testing-with-postman)

---

## ✅ Features

- 📌 Create a new task  
- 📂 View all tasks  
- 🔍 View a specific task  
- ✏️ Update a task  
- ❌ Delete a task  

---

## 🛠 Tools & Technologies

- [Laravel](https://laravel.com/)
- [PHP](https://www.php.net/) 8.2 or higher
- [Composer](https://getcomposer.org/)
- [XAMPP](https://www.apachefriends.org/) / [MySQL](https://www.mysql.com/)
- [Postman](https://www.postman.com/)

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Create new laravel project
    composer create-project laravel/laravel project-name
### 2️⃣ Install required packages (API)
    php artisan install:api
### 3️⃣ Create database
[Localhost](https://localhost/phpmyadmin) https://localhost/phpmyadmin
create new database

### 4️⃣ Update .env file of project 
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306    
    DB_DATABASE=database_name
    DB_USERNAME=root
    DB_PASSWORD=

### 5️⃣ Run migration
    php artisan migrate
### 6️⃣ Run the project
    php artisan serve
### 7️⃣ Open Postman and send API requests
- [Create a new task](#-create-a-new-task)
- [View all tasks](#-view-all-tasks)
- [View a specific task](#-view-a-specific-task)
- [Update a task](#-update-a-task)
- [Delete a task](#-delete-a-task)

| **Method** | **Endpoint**         | **Description**             |
|------------|----------------------|-----------------------------|
| `GET`      | `/api/tasks`         | Get all tasks               |
| `GET`      | `/api/tasks/{id}`    | Get a task by ID            |
| `POST`     | `/api/tasks`         | Create a new task           |
| `PUT`      | `/api/tasks/{id}`    | Update an existing task     |
| `DELETE`   | `/api/tasks/{id}`    | Delete a task               |

