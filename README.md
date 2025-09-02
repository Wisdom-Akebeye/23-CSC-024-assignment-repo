Student Registration System

Name: Akebeye, Wisdom Sunday

Matric Number: 23/CSC/024
Course Code: CSC 282
Assignment Title: Student Registration Web Application

Project Description This is a simple PHP web application for registering students into a MySQL database.
It includes:

A form to register students.
Validation for required fields and valid email.
A page to view all registered students.
Ability to delete student records (extra credit).
Setup Instructions

Requirements
PHP (7.x or later)
MySQL
Web server (XAMPP/WAMP/LAMP or MAMP recommended)
Git (optional, for cloning)
Database Setup

Open phpMyAdmin (http://localhost/phpmyadmin)

Create a database called student_db.

Import the file student_db.sql located in the project folder.

This will create the student_records table automatically.
Running the Application

Place the project folder (student_app) inside your server’s htdocs (for XAMPP) or www (for WAMP/MAMP).

Start Apache and MySQL in XAMPP Control Panel.

Open your browser and go to: http://localhost/student_app/index.php

Features

✅ Student registration form
✅ Validation (all fields required, email format check)
✅ Display registered students
✅ Delete option beside each record
🗂 Project Structure student_app/ │── index.php Student registration form │── process.php Handles form submission & inserts into DB │── view.php Displays registered students & delete option │── style.css Stylesheet for UI │── student_db.sql Database script │── README.md Project documentation

Author Akebeye Wisdom Sunday
Matric Number: 23/CSC/024
