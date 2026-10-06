# 🛒 ShopSphere – Django eCommerce Website

ShopSphere is a full-stack eCommerce web application built with **Python and Django**. It provides a complete online shopping workflow including user authentication, product browsing, shopping cart management, checkout, payment integration, order processing, and product/order administration.

The project also includes a responsive frontend, product image management, email verification, static file handling, and deployment configuration.

---

## 🚀 Live Demo

🌐 **Live Website:**  
https://shopsphere-l2s6.onrender.com/

> The application is deployed as a Django web application on Render.

---

## ✨ Features

### 👤 User Authentication
- User registration
- User login and logout
- User authentication
- Email verification
- User profile functionality

### 🛍️ Product Management
- Product listing
- Product detail pages
- Product images
- Product categories/details
- Admin-side product management

### 🛒 Shopping Cart
- Add products to cart
- Update cart items
- Remove products
- View cart contents
- Cart quantity management

### 💳 Checkout & Payment
- Checkout workflow
- Payment integration using PayTM
- Payment verification
- Order creation after checkout

### 📦 Order Management
- Order processing
- Order history
- Order details
- Admin order management

### 🔐 Admin Panel
- Manage products
- Manage users
- Manage orders
- Manage application data through Django Admin

### 🎨 Frontend
- HTML templates
- CSS
- JavaScript
- Bootstrap-based styling
- Responsive design
- Product images and media

### ⚙️ Deployment
- Gunicorn production server
- WhiteNoise static file serving
- Render deployment support
- Static file collection using Django

---

## 🛠️ Technologies Used

### Backend
- Python
- Django 5.1.3
- Django Templates
- Django Authentication
- Django ORM

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Database
- SQLite

### Payment
- PayTM Payment Gateway
- PyCryptodome

### Email & Authentication
- Django Email Verification
- SMTP

### Deployment & Production
- Gunicorn
- WhiteNoise
- Render

### Development Tools
- Git
- GitHub
- VS Code

---

## 📁 Project Structure

```text
ShopSphere/
│
├── frontend/
│   └── Tempo/
│       └── Tempo/
│           ├── assets/
│           ├── forms/
│           ├── blog-details.html
│           ├── blog.html
│           ├── index.html
│           ├── portfolio-details.html
│           ├── service-details.html
│           ├── starter-page.html
│           ├── Tempo.zip
│           └── Readme.txt
│
├── shopy/
│   │
│   ├── PayTm/
│   │   ├── __init__.py
│   │   └── Checksum.py
│   │
│   ├── app/
│   │   ├── migrations/
│   │   ├── templates/
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── views.py
│   │   └── ...
│   │
│   ├── authen/
│   │   ├── migrations/
│   │   ├── templates/
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── views.py
│   │   └── ...
│   │
│   ├── media/
│   │   └── images/
│   │
│   ├── shopy/
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   │
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   ├── login.html
│   │   ├── signup.html
│   │   └── ...
│   │
│   ├── build_files.sh
│   ├── db.sqlite3
│   ├── manage.py
│   ├── readme.md
│   ├── requirements.txt
│   └── vercel.json
│
├── requirements.txt
│
└── README.md
