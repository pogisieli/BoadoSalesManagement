# 🧾 Sales Management System

## 📖 Description / Overview
The **Sales Management System** is designed to help businesses efficiently manage product sales, customer transactions, and revenue tracking.  
It supports essential sales operations to improve workflow, accuracy, and overall productivity.  

This project was developed as part of our **Midterm Examination** to demonstrate understanding of transaction processes and fundamental system development concepts.

---

## 🎯 Objectives
- Provide a reliable system for managing sales transactions  
- Track customer purchases and product availability  
- Reduce human error in manual recording of sales  
- Improve reporting and monitoring of business performance  
- Apply learned programming and system development skills  

---

## ✅ Features / Functionality
- ➕ Add, edit, and delete products  
- 🧾 Manage customer transactions and sales records  
- 💰 View total income or sales reports  
- 💻 Simple and user-friendly interface  
- ⚙️ Data validation to avoid incorrect inputs  

---

## 🛠 Installation Instructions

Follow these steps to set up and run the **Sales Management System** properly:

```bash
Step 1 — Clone or Download the Project
Download the project from GitHub or clone it using the command:

git clone https://github.com/pogisieli/BoadoSalesManagement.git

cd SalesManagementSystem

---

Step 2 — Navigate to the Project Folder
Use your terminal or file explorer to enter the project folder:

cd SalesManagementSystem

---

Step 3 — Install Dependencies (If Applicable)
If your project uses Node.js or any package manager, run:

npm install

Skip this step if the project is purely PHP or Python-based.

For PHP projects, make sure the following extensions are enabled in php.ini:

extension=mysqli
extension=pdo_mysql

---

Step 4 — Set Up the Database

1. Open XAMPP, Laragon, or WAMP, and start Apache and MySQL.
2. Go to http://localhost/phpmyadmin
3. Create a new database (example: sales_db).
4. Import the SQL file included in the project folder (database.sql or similar).
5. Update your database configuration file (for example config.php or .env) with your local credentials:

$host = "localhost";
$user = "root";
$password = "";
$database = "sales_db";

---

Step 5 — Configure the Environment
If your system uses an environment file:

1. Copy the example configuration file:

cp .env.example .env

2. Update .env with your correct database and server details.
Example .env:

DB_HOST=localhost
DB_USER=root
DB_PASS=
DB_NAME=sales_db
APP_ENV=local
APP_DEBUG=true

---

Step 6 — Start Your Local Server
Place your project folder inside your htdocs (for XAMPP) or www directory (for WAMP).
Then, run your server:
For XAMPP users:
Open the XAMPP Control Panel
Start Apache and MySQL

---

Step 7 — Access the System
Open your browser and visit:

http://localhost/SalesManagementSystem

or if your folder name differs:
http://localhost/YourFolderName

If it’s a web app using Node.js or another backend, you can run:
npm start

and visit:
http://localhost:3000

---

Step 8 — Log In and Test

Use the default credentials (if provided in the project).
Add sample products, perform a transaction, and check the sales report to verify everything works.

---

You can paste this right below your `## 🛠 Installation Instructions` heading — it’s fully formatted and Markdown-ready ✅

---

Contributors

Elijah Nathan T. Boado
Marben Antony L. Madrio

---

Notes

This README.md serves as the official documentation for the Midterm Project.
Make sure to include real screenshots, correct file paths, and accurate setup instructions before submission.
