# 🛒 Blinkit Clone

A fully functional e-commerce web application inspired by **Blinkit** (formerly Grofers), built with PHP, MySQL, and WordPress. Supports complete shopping flow from product browsing to order tracking.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Hostinger](https://img.shields.io/badge/Deployed%20on-Hostinger-673DE6?style=for-the-badge)

---

## 📌 About the Project

This project is a clone of the popular instant grocery delivery platform **Blinkit**. It was built to simulate a real-world e-commerce experience with a clean, responsive UI and a robust backend.

> **Domain:** E-Commerce  
> **Type:** Academic / Personal Project  
> **Developed:** July 2024

---

## ✨ Features

- 🏠 **Home Page** — Featured products, categories, and banners
- 🔍 **Product Browsing** — Browse products by category with search functionality
- 🛒 **Shopping Cart** — Add, remove, and update product quantities
- 💳 **Checkout** — Smooth checkout flow with order summary
- 📦 **Order Tracking** — Track placed orders and their status
- 📱 **Responsive UI** — Works seamlessly across mobile, tablet, and desktop
- 🗄️ **Database Driven** — All products, users, and orders stored in MySQL

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL |
| CMS | WordPress |
| Hosting | Hostinger |

---

## 🗂️ Database Design

- **ER Schema** designed to handle users, products, categories, cart, and orders
- **UML Diagrams** created for system architecture and use-case modeling
- Normalized database structure for efficient querying

---


---

## 🚀 Getting Started

### Prerequisites
- PHP >= 7.4
- MySQL
- WordPress installed
- Web server (Apache/Nginx) or XAMPP locally

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/tharunalamasu/blinkit-clone.git

# 2. Navigate to the project folder
cd blinkit-clone

# 3. Import the database
# Open phpMyAdmin → Create a new database → Import blinkit.sql

# 4. Configure database connection
# Edit wp-config.php with your DB credentials
define('DB_NAME', 'your_database_name');
define('DB_USER', 'your_username');
define('DB_PASSWORD', 'your_password');
define('DB_HOST', 'localhost');

# 5. Start your local server and open in browser
http://localhost/blinkit-clone
```

---

## 📁 Project Structure

```
blinkit-clone/
├── wp-content/
│   ├── themes/
│   │   └── blinkit-theme/     # Custom theme files
│   └── plugins/               # Required plugins
├── assets/
│   ├── css/                   # Stylesheets
│   ├── js/                    # JavaScript files
│   └── images/                # Product & UI images
├── includes/
│   ├── cart.php               # Cart logic
│   ├── checkout.php           # Checkout process
│   └── orders.php             # Order management
├── database/
│   └── blinkit.sql            # Database schema & seed data
└── README.md
```

---

## 📊 UML & ER Diagrams

> *Add your UML and ER diagram images here*

- **Use Case Diagram** — User interactions with the system
- **ER Diagram** — Entity relationships for the database
- **Class Diagram** — Object structure of the application

---

## 🌐 Live Demo

🔗 [View Live on Hostinger](#) *(add your deployed link here)*

---

## 🙋‍♂️ Author

**Tharun Nalamasu**  
📧 tharunnalamasu@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/tharunnalamasu) · [GitHub](https://github.com/tharunalamasu)

---

## 📄 License

This project is for educational purposes. Feel free to fork and build upon it.

---

<div align="center">
  <i>⭐ If you found this useful, consider giving it a star!</i>
</div>
