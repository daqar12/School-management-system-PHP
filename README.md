
# 🏫 Professional School Management System

**ID:** C1220116  
**Name:** Mohamed Dahir Abdullahi  
**Class:** CA222

A modern, robust web application built with **PHP** and **MySQL** to manage educational institutions. This system features a dynamic dashboard, secure authentication, and a centralized API handler for administrative tasks.

## ✨ Key Features

* **Secure Authentication:** Multi-user login system with session management (Admin/Staff/Student).
* **Dynamic Dashboard:** Real-time statistics for students, staff, and revenue using Chart.js.
* **Centralized API Handler:** A unified `api_handler.php` to manage CRUD operations (Create, Read, Update, Delete) via AJAX.
* **Comprehensive Data Management:** Specific modules for Students, Teachers, Classes, Payments, Receipts, and Attendance.
* **Modern UI:** Responsive design built with **Bootstrap 5**, **Inter Font**, and **Bootstrap Icons**.
* **Database Safety:** Uses PHP Data Objects (PDO) with prepared statements to prevent SQL injection.

## 🛠️ Tech Stack

* **Backend:** PHP 
* **Database:** MySQL
* **Frontend:** HTML5, CSS3 (Custom Properties), JavaScript (ES6+), Bootstrap 5
* **Charts:** Chart.js

## 📂 Project Structure

* `index.php` - The main application shell and sidebar navigation.
* `login.php` / `logout.php` - Secure session control.
* `db.php` - Centralized PDO database connection configuration.
* `api_handler.php` - The backend engine handling all AJAX requests and table logic.
* `content_dashboard.php` - The visual analytics and summary view.
* `content_table.php` - A high-fidelity dynamic table viewer for all database records.
* `check_schema.php` - A utility tool for verifying database table structures.

## 🚀 Installation Guide

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/daqar12/School-management-system-PHP]
    ```
2.  **Server Setup:**
    * Move the project folder to your local server directory (e.g., `C:/xampp/htdocs/`).
    * Ensure **Apache** and **MySQL** are running in XAMPP.
3.  **Database Configuration:**
    * Create a database named `SCHOOLDB` in phpMyAdmin.
    * Import your `.sql` file (if provided) or use the structures defined in `check_schema.php`.
    * Update `db.php` with your local database credentials if they differ.
4.  **Run the App:**
    * Navigate to `http://localhost/school_management_sm1-main/login.php`.

## 🔒 Security Features
* **Prepared Statements:** All database queries are handled via PDO to block SQL injection.
* **Session Validation:** Strict checks on `index.php` to ensure only logged-in users can access the system.
* **Table Whitelisting:** The API handler only interacts with predefined allowed tables.

---
Developed with team of class CA222.
ID:                  Name:
C1220116             Mohamed Dahir Abdullahi
C1220130             Anas Liban Ahmed
C1220085             Abdinasir Ali Farah
C1220851             Mohamed Dahir Hashi
C1220097             Isamil Omar Gele

