# Lost and Found System

## 🚀 Project Overview

Lost and Found System is a modern web application for managing lost and found items, user accounts, payments, and gift items. Built with PHP, MySQL, and Bootstrap 5, it provides a seamless experience for users and administrators.

---

## 🧩 Features

- Secure user registration and login
- Submit and manage lost or found items
- Browse and claim gift items
- Payment processing for item claims
- Admin dashboard for user and item management
- Responsive design with Bootstrap 5

---

## 🗄️ Database Structure

| Table          | Purpose                    |
| -------------- | -------------------------- |
| `users`        | User accounts and roles    |
| `gift_items`   | Items available as gifts   |
| `payments`     | Payment transactions       |
| `submit_items` | Submitted lost/found items |

---

## ⚡ Quick Start

1. Import `dump.sql` and `dump1.sql` into your MySQL database.
2. Update database credentials in `pages/dbconfig.php` if needed.
3. Place the project folder in your web server directory (e.g., `htdocs` for XAMPP).
4. Open your browser and go to: `http://localhost/Lost-And-Found/pages/index.php`

---

## 🛠️ Technologies Used

- PHP
- MySQL/MariaDB
- Bootstrap 5

---

## 📁 Folder Structure

```
Lost-And-Found/
├── pages/         # PHP pages for the app
├── css/           # Custom styles
├── images/        # Item and UI images
├── bootstrap-5.3.3-dist/ # Bootstrap assets
├── dump.sql       # Main database dump
├── dump1.sql      # Additional database dump
```

---

## 📜 License

MIT
