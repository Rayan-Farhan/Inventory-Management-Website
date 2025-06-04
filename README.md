# Inventory Management System (PHP + MySQL)

This is a lightweight Inventory Management System built using **PHP**, **MySQL**, and **HTML/CSS**. It allows managing products, customers, suppliers, inventory, and orders — with a special feature for **forecasting next month’s sales**.

---

## Features

- Add/Edit/Delete:
  - Products
  - Customers
  - Orders & Order Details
  - Inventory
  - Suppliers
- **Next Month Sales Forecasting**
  - Based on historical sales data using basic statistical methods (see `forecast.php`)
  - Helps in planning inventory more efficiently

---

## Technology Stack

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** MySQL (phpMyAdmin via XAMPP)
- **Forecasting:** PHP-based implementation using past order data

---

## How to Run the Project (Using XAMPP)

### 1. Install XAMPP
- Download from official website
- Start **Apache** and **MySQL** from the XAMPP Control Panel

### 2. Setup Project
- Unzip this folder and move it to:  
  `C:\xampp\htdocs\Inventory_DataBase`

### 3. Create the Database

### 4. Configure `connection.php`
Edit the following file:
```php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "inventory_db";
```

### 5. Run the App
- Visit this URL in your browser: http://localhost/Inventory_DataBase/
