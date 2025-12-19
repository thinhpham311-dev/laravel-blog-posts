# Laravel Blog Post

A simple and scalable **Blog Post application** built with **Laravel**, providing core blogging features such as authentication, post management, and role-based access control.  
This project is designed for **local development** and can be easily deployed to production.

---

## 🔗 Demo

This project is currently running on a **local development environment**.  
To view and test the application, please follow the installation and setup instructions below.

---

## 📌 Features

- User authentication (Register / Login / Logout)
- Role-based access control (Admin / User)
- Blog post CRUD (Create, Read, Update, Delete)
- Categories and tags management
- SEO-friendly slug URLs
- Image upload for blog posts
- Pagination and search functionality
- Authorization using Laravel Policies
- RESTful API ready (optional)

---

## 🛠️ Technologies Used

**Backend**
- Laravel 10+
- PHP 8+
- Eloquent ORM
- Laravel Artisan

**Frontend**
- Blade Template Engine
- Tailwind CSS / Bootstrap (optional)

**Database**
- MySQL / PostgreSQL / SQLite

**Tools**
- Composer
- Git

---

## 📂 Project Structure

```bash
laravel-blog-post/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Requests/
│   ├── Models/
│   └── Policies/
├── database/
│   ├── migrations/
│   └── seeders/
├── resources/
│   ├── views/
│   └── css/
├── routes/
│   ├── web.php
│   └── api.php
├── public/
├── storage/
└── README.md
```

## ▶️ How to Run the Project (Local)

## Prerequisites
Make sure your local machine has the following installed:

- PHP >= 8.1
- Composer
- MySQL (or PostgreSQL / SQLite)
- Node.js & npm (if using Vite / Tailwind)

## Check versions:
```bash
php -v
composer -V
node -v
```

## Step 1: Clone the repository
git clone https://github.com/your-username/laravel-blog-post.git
cd laravel-blog-post

## Step 2: Install PHP dependencies
```bash
composer install
```

## Step 3: Create environment file
cp .env.example .env
php artisan key:generate

## Step 4: Configure database
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_blog
DB_USERNAME=root
DB_PASSWORD=
```

## Step 5: Run migrations and seeders
```bash
php artisan migrate --seed
```

## Step 6: Start the development server
```bash
php artisan serve
```
