 # Online Shopping Management System

## Project Overview

The Online Shopping Management System is a web-based e-commerce application developed as a Database Systems project. The system allows customers to browse products, manage shopping carts, place orders, and view order history. Administrators can manage products, categories, inventory, and customer orders through an admin dashboard.

The project demonstrates the practical implementation of relational database concepts including database design, normalization, SQL queries, views, triggers, stored procedures, and frontend-backend integration using PHP and MySQL.

---

## Project Objectives

- Design and implement a relational database for an online shopping platform.
- Manage customer, product, category, order, and payment information.
- Apply database normalization techniques to reduce redundancy.
- Implement SQL queries, views, triggers, and stored procedures.
- Develop a functional web application using PHP and MySQL.
- Demonstrate CRUD (Create, Read, Update, Delete) operations.

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Backend
- PHP 8+

### Database
- MySQL

### Development Tools
- XAMPP
- MySQL Workbench
- Draw.io
- GitHub

---

## System Features

### Customer Features

- User Registration
- User Login and Logout
- Browse Products
- Search Products
- View Product Details
- Add Products to Cart
- Update Cart Quantity
- Remove Products from Cart
- Place Orders
- View Order History

### Admin Features

- Admin Login
- Manage Products
- Add Products
- Update Products
- Delete Products
- Manage Categories
- View Customer Orders
- Manage Inventory

---

## Database Tables

| Table Name | Description |
|------------|-------------|
| Customer | Stores customer information |
| Category | Stores product categories |
| Product | Stores product details |
| Cart | Stores customer shopping carts |
| CartItem | Stores products added to carts |
| Orders | Stores customer orders |
| OrderDetails | Stores ordered products |
| Payment | Stores payment records |
| Admin | Stores administrator information |

---

## Frontend Pages

### Customer Module

| Page | Description |
|--------|-------------|
| index.php | Home Page |
| login.php | Customer Login |
| register.php | Customer Registration |
| products.php | Product Listing |
| product-details.php | Product Details |
| cart.php | Shopping Cart |
| checkout.php | Order Checkout |
| orders.php | Order History |

### Admin Module

| Page | Description |
|--------|-------------|
| dashboard.php | Admin Dashboard |
| products.php | Product Management |
| categories.php | Category Management |
| orders.php | Order Management |

---

## Project Structure

```text
Online-Shopping-Management-System/
│
├── README.md
├── ER_Diagram.png
├── Relational_Schema.png
│
├── database/
│   ├── create_tables.sql
│   ├── insert_sample_data.sql
│   ├── queries.sql
│   ├── views.sql
│   ├── triggers.sql
│   └── procedures.sql
│
├── frontend/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   ├── images/
│   │
│   ├── includes/
│   │   ├── db.php
│   │   ├── header.php
│   │   └── footer.php
│   │
│   ├── index.php
│   ├── login.php
│   ├── register.php
│   ├── products.php
│   ├── product-details.php
│   ├── cart.php
│   ├── checkout.php
│   └── orders.php
│
├── admin/
│   ├── dashboard.php
│   ├── products.php
│   ├── categories.php
│   └── orders.php
│
├── screenshots/
│   ├── homepage.png
│   ├── login-page.png
│   ├── products-page.png
│   ├── cart-page.png
│   ├── checkout-page.png
│   └── admin-dashboard.png
│
└── documentation/
    ├── SRS_Document.pdf
    ├── Normalization.pdf
    ├── Presentation.pptx
    └── Project_Report.pdf
```

---

## Database Concepts Implemented

- Entity Relationship Diagram (ERD)
- Relational Schema
- Database Normalization (3NF)
- Primary Keys
- Foreign Keys
- SQL Queries
- Joins
- Aggregate Functions
- Views
- Triggers
- Stored Procedures

---

## Documentation

### ER_Diagram.png
Contains the Entity Relationship Diagram showing entities, attributes, and relationships.

### Relational_Schema.png
Contains the relational schema derived from the ER Diagram showing tables, primary keys, and foreign keys.

### SRS_Document.pdf
Software Requirements Specification document.

### Normalization.pdf
Contains normalization process from UNF to 3NF.

### Project_Report.pdf
Complete project report including database design, SQL implementation, and frontend screenshots.

### Presentation.pptx
Project presentation for final demonstration and viva.

---

## Future Enhancements

- Product Reviews and Ratings
- Wishlist Functionality
- Discount Coupons
- Online Payment Gateway
- Order Tracking System
- Product Recommendation System
- Sales Analytics Dashboard

---

## Developed By

**Muhammad Tayyab**

**Course:** Database Systems

**Semester:** 5th Semester

**Department:** Computer Science

**University:** The University of Lahore

---

## License

This project is developed for academic and educational purposes only.
