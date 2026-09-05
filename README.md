# 🎓 Student Management System

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:0B5ED7,100:00C2FF&height=180&section=header&text=Student%20Management%20System&fontSize=42&fontColor=FFFFFF&fontAlignY=40" width="100%"/>

### Role-based school management platform built with Laravel.

<img src="https://img.shields.io/badge/Laravel-PHP-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Role%20Based-Access-1F6FEB?style=for-the-badge" />

</div>

---

## 📌 Overview

The **Student Management System** is a Laravel-based, role-oriented school management application designed to organize common academic and administrative workflows.

The application follows a multi-role approach for **administrators, teachers, parents and students**, providing each user type with an appropriate experience.

## 👥 Roles

| Role | Purpose |
|---|---|
| 👑 **Admin** | Manage the overall system and users |
| 🧑‍🏫 **Teacher** | Work with teaching-related workflows |
| 👨‍👩‍👧 **Parent** | Access student/parent-facing information |
| 🎓 **Student** | Access student-facing functionality |

## ✨ Highlights

- 🔐 Role-based access control
- 🏫 School management workflows
- 👨‍🎓 Student-oriented management
- 🧑‍🏫 Teacher-oriented workflows
- 👨‍👩‍👧 Parent access
- 🗄️ Laravel ORM and migrations
- 🧩 Permission management with Spatie Laravel Permission

## 🛠️ Technology Stack

- **Laravel / PHP**
- **MySQL**
- **JavaScript / npm**
- **Composer**
- **Spatie Laravel Permission**

## 🚀 Installation

```bash
git clone https://github.com/Vivek99256/student-management-system.git
cd student-management-system
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
```

Then open **http://127.0.0.1:8000**.

## 🏗️ Role Architecture

```text
                     APPLICATION
                          │
                 Authentication
                          │
        ┌─────────────────┼─────────────────┐
        ↓                 ↓                 ↓
      ADMIN            TEACHER            USER
                                          /   \
                                         ↓     ↓
                                      PARENT  STUDENT
        │                 │                 │
        └─────────────────┼─────────────────┘
                          ↓
                 School Workflows
```

## 🔐 Security Note

For local/demo environments, use test credentials only. **Never use simple demo passwords in production.** Configure strong credentials and secure environment variables before deployment.

## 👨‍💻 Author

**Vivek Gajera** — Full Stack Developer

[![GitHub](https://img.shields.io/badge/GitHub-Vivek99256-181717?style=for-the-badge&logo=github)](https://github.com/Vivek99256)

<div align="center">⭐ Built for learning, experimentation and practical education workflows.</div>
