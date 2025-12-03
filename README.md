📰 News Portal Project in PHP & MySQL

A simple and efficient News Portal Web Application built using PHP, MySQL, HTML, CSS, and Bootstrap.This project allows admins to publish, update, and manage news articles, categories, and user comments. It is perfect for beginners learning web development and CRUD operations with PHP.

🚀 Features 👤 Admin Panel Admin Login Manage Categories (Add / Edit / Delete) Manage Sub-categories Manage News Posts Upload Images for News Activate/Deactivate News View Comments from Visitors

🌐 User Side View Latest & Trending News Filter News by Category & Subcategory News Details Page with Full Article Comment System for Users Search Functionality

🛠️ Tech Stack Component Technology Frontend HTML, CSS, Bootstrap Backend PHP (Core PHP) Database MySQL Server XAMPP / WAMP / LAMP Others jQuery

📁 Project Folder Structure News-Portal-Project/ │── admin/ # Admin dashboard │── includes/ # Common PHP include files │── images/ # Uploaded images │── js/ # Javascript files │── css/ # Stylesheets │── news-details.php # Single article page │── index.php # Homepage │── contact-us.php │── about-us.php │── config.php # Database connection │── admin.sql # Database file

⚙️ Installation Guide 1️⃣ Download or Clone the Project git clone https://github.com/yourusername/news-portal-project.git 2️⃣ Move Project to Server Folder

For XAMPP: C:/xampp/htdocs/news-portal/

3️⃣ Import the Database Open phpMyAdmin Create a database → newsportal Import admin.sql (located inside the project folder)

4️⃣ Configure Database Connection Open config.php and update: $host = "localhost"; $user = "root"; $pass = ""; $dbname = "newsportal";

5️⃣ Run the Project

http://localhost/news-portal/
