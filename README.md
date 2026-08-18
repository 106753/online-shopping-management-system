 # Online Shopping Management System

## Project Overview

The **Online Shopping Management System** is a web-based e-commerce application developed as a Database Systems project. The system allows customers to browse products, manage shopping carts, place orders, and view order history. Administrators can manage products, categories, inventory, and customer orders through an admin dashboard.

The project demonstrates the practical implementation of relational database concepts including database design, normalization, SQL queries, views, triggers, stored functions, CRUD operations, and frontend-backend integration using **Python and Flask with PostgreSQL**.

---

## Project Objectives

* Design and implement a relational database for an online shopping platform.
* Manage customer, product, category, order, and payment information.
* Apply database normalization techniques up to Third Normal Form (3NF).
* Implement SQL queries, views, triggers, and stored functions.
* Develop a functional web application using Python and Flask.
* Use PostgreSQL for database management.
* Demonstrate CRUD (Create, Read, Update, Delete) operations.
* Establish relationships between database tables using Primary Keys and Foreign Keys.

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap 5

### Backend

* Python 3
* Flask

### Database

* PostgreSQL

### Database Management

* pgAdmin 4

### Development Tools

* Visual Studio Code
* Draw.io
* Git
* GitHub

---

## System Features

### Customer Features

* User Registration
* User Login and Logout
* Browse Products
* Search Products
* View Product Details
* Add Products to Cart
* Update Cart Quantity
* Remove Products from Cart
* Place Orders
* View Order History
* View Payment Information

### Admin Features

* Admin Login
* Admin Dashboard
* Manage Products
* Add Products
* Update Products
* Delete Products
* Manage Categories
* View Customer Orders
* Update Order Status
* Manage Inventory

---

## Database Tables

| Table Name   | Description                      |
| ------------ | -------------------------------- |
| Customer     | Stores customer information      |
| Category     | Stores product categories        |
| Product      | Stores product details           |
| Cart         | Stores customer shopping carts   |
| CartItem     | Stores products added to carts   |
| Orders       | Stores customer orders           |
| OrderDetails | Stores ordered products          |
| Payment      | Stores payment records           |
| Admin        | Stores administrator information |

---

## Database Relationships

| Parent Table | Child Table  | Relationship |
| ------------ | ------------ | ------------ |
| Customer     | Orders       | 1 : Many     |
| Customer     | Cart         | 1 : 1        |
| Category     | Product      | 1 : Many     |
| Cart         | CartItem     | 1 : Many     |
| Product      | CartItem     | 1 : Many     |
| Orders       | OrderDetails | 1 : Many     |
| Product      | OrderDetails | 1 : Many     |
| Orders       | Payment      | 1 : 1        |

---

## Frontend Pages

### Customer Module

| Page                   | Description           |
| ---------------------- | --------------------- |
| `index.html`           | Home Page             |
| `login.html`           | Customer Login        |
| `register.html`        | Customer Registration |
| `products.html`        | Product Listing       |
| `product-details.html` | Product Details       |
| `cart.html`            | Shopping Cart         |
| `checkout.html`        | Order Checkout        |
| `orders.html`          | Order History         |

### Admin Module

| Page              | Description         |
| ----------------- | ------------------- |
| `dashboard.html`  | Admin Dashboard     |
| `products.html`   | Product Management  |
| `categories.html` | Category Management |
| `orders.html`     | Order Management    |

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
│   └── online_shopping_db.sql
│
├── backend/
│   ├── app.py
│   ├── config.py
│   ├── database.py
│   │
│   ├── routes/
│   │   ├── auth.py
│   │   ├── products.py
│   │   ├── cart.py
│   │   ├── orders.py
│   │   └── admin.py
│   │
│   └── requirements.txt
│
├── frontend/
│   ├── templates/
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── products.html
│   │   ├── product-details.html
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   └── orders.html
│   │
│   └── static/
│       ├── css/
│       │   └── style.css
│       │
│       ├── js/
│       │   └── script.js
│       │
│       └── images/
│
├── admin/
│   └── templates/
│       ├── dashboard.html
│       ├── products.html
│       ├── categories.html
│       └── orders.html
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

* Entity Relationship Diagram (ERD)
* Relational Schema
* Database Normalization (3NF)
* Primary Keys
* Foreign Keys
* Referential Integrity
* SQL Queries
* JOIN Operations
* Aggregate Functions
* GROUP BY
* Views
* Triggers
* Stored Functions
* DDL Commands
* DML Commands
* DQL Commands
* DCL Commands
* CRUD Operations

---

## SQL Implementation

The complete PostgreSQL implementation is stored in:

```text
database/online_shopping_db.sql
```

The SQL file contains:

* `CREATE TABLE` statements
* Primary Keys
* Foreign Keys
* Constraints
* Sample `INSERT` statements
* `SELECT` queries
* JOIN queries
* `UPDATE` queries
* `DELETE` queries
* Aggregate queries
* `GROUP BY` queries
* Views
* Triggers
* Stored Functions
* `GRANT` and `REVOKE` commands

---

## Documentation

### ER_Diagram.png

Contains the Entity Relationship Diagram showing entities, attributes, Primary Keys, Foreign Keys, and relationships.

### Relational_Schema.png

Contains the relational schema derived from the ER Diagram showing tables, Primary Keys, Foreign Keys, and relationships.

### SRS_Document.pdf

Software Requirements Specification document containing:

* Project Scenario
* Project Scope
* Project Requirements
* Functional Requirements
* Non-Functional Requirements
* System Users
* System Features

### Normalization.pdf

Contains the database normalization process from:

* Unnormalized Form (UNF)
* First Normal Form (1NF)
* Second Normal Form (2NF)
* Third Normal Form (3NF)

### Project_Report.pdf

Contains:

* Project Introduction
* Problem Statement
* Project Objectives
* Project Scenario
* Project Requirements
* System Features
* ER Diagram
* Relational Schema
* Normalization
* Database Tables
* SQL Implementation
* SQL Queries
* Views
* Triggers
* Stored Functions
* Frontend Screenshots
* Testing
* Conclusion

### Presentation.pptx

Contains the project presentation prepared for final demonstration and viva.

---

## Future Enhancements

* Product Reviews and Ratings
* Wishlist Functionality
* Discount Coupons
* Online Payment Gateway
* Order Tracking System
* Product Recommendation System
* Sales Analytics Dashboard
* Customer Feedback System

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
