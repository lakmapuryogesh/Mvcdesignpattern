📌 Project Title

Java Servlet & JSP MVC Web Application

📖 Overview

This project is a simple Java web application demonstrating the MVC (Model–View–Controller) architecture using Servlets, JSP, and a MySQL database.

<img width="976" height="653" alt="Screenshot 2025-08-15 150237" src="https://github.com/user-attachments/assets/d432e979-54bd-401d-8ec3-dbda098d8682" />

It supports:

User Registration

User Login

Session Handling

Profile Viewing

Logout

🗂️ Project Structure
1. Controller (Servlets)

Register.java → Handles user registration form submission.

Login.java → Handles login form submission.

Logout.java → Manages session logout.

2. Model (Java Class)

User.java → A simple Java bean to hold user data.

3. View (HTML/JSP)

index.html → Entry page.

register.html → Registration form.

login.html → Login form.

profile.jsp → Displays logged-in user profile.

🗄️ Database

Table: register

name	email	password	city
John	john@email.com	pass123	New York
🔄 MVC Flow

Client sends request via HTML form.

Controller (Servlet) processes request and interacts with the Model.

Model handles database operations and returns data to the Controller.

View (JSP) displays the results to the user.

⚙️ Technologies Used

Java Servlets

JSP

MySQL

JDBC

HTML/CSS

Apache Tomcat

🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/your-repo.git


Import into Eclipse/IntelliJ as a Dynamic Web Project.

Set up MySQL database:

CREATE DATABASE mydb;
USE mydb;
CREATE TABLE register(
    name VARCHAR(50),
    email VARCHAR(50),
    password VARCHAR(50),
    city VARCHAR(50)
);


Configure DB credentials in DbConnection.java.

Deploy on Apache Tomcat and run.

📌 Features

✅ User Registration

✅ User Login

✅ Session Tracking

✅ MVC Architecture
