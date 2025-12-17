# Facebook User Profile Clone 👤

This project is a **Facebook user profile clone** built using **Laravel**. It focuses on replicating the **core layout and functionality of a Facebook-style user profile**, serving as a learning and practice project for Laravel-based application development.

> ⚠️ **Project Status:** Incomplete / Work in Progress

---

## 🚀 Project Overview

The Facebook User Profile Clone is designed to demonstrate how modern social media profile features can be structured using Laravel’s MVC architecture. The project emphasizes **backend logic, routing, authentication, and UI structuring**, rather than being a full production-ready social network.

This project is ideal for:

* Practicing Laravel fundamentals
* Understanding user authentication and profile management
* Exploring database relationships in social applications

---

## 🛠️ Tech Stack

* **Backend:** Laravel (PHP Framework)
* **Frontend:** Blade Templates
* **Styling:** CSS / Bootstrap
* **Database:** MySQL
* **Architecture:** MVC (Model–View–Controller)

---

## ✨ Implemented Features

* User authentication (registration & login)
* Basic user profile layout
* Profile information display
* Laravel routing and controllers
* Database migrations and models

---

## 🚧 Pending / Planned Features

* Profile picture upload
* Friends / follow system
* Posts and timeline
* Likes and comments
* Notifications
* Real-time interactions

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/facebook-user-profile-clone.git
cd facebook-user-profile-clone
```

### 2. Install Dependencies

```bash
composer install
```

### 3. Environment Configuration

```bash
cp .env.example .env
```

Update database credentials in `.env`:

```env
DB_DATABASE=facebook_clone
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Generate Application Key

```bash
php artisan key:generate
```

### 5. Run Migrations

```bash
php artisan migrate
```

### 6. Start Development Server

```bash
php artisan serve
```

Access the application at:

```
http://127.0.0.1:8000
```

---

## 📂 Project Structure

* `app/` – Controllers and Models
* `resources/views/` – Blade templates
* `routes/web.php` – Web routes
* `database/migrations/` – Database schema
* `public/` – Public assets

---

## 🎯 Purpose of the Project

* Practice Laravel application development
* Understand social media profile workflows
* Build confidence with MVC-based systems
* Serve as a foundation for future feature expansion

---

## 🤝 Contribution

This project is open for learning and collaboration.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

---

## 📄 License

This project is for educational purposes and is available under the **MIT License**.

---

## 👨‍💻 Author

**Mutwiri**
Laravel Developer | Backend & Web Applications

---

> *A learning-focused Laravel project inspired by Facebook user profiles.*
