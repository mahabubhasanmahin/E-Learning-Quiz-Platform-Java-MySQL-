# 📚 E-Learning Quiz Platform (Java + MySQL)

A simple desktop-based quiz platform built using **Java Swing** and **MySQL**. This project demonstrates user authentication and basic structure for managing quiz topics and questions.

---

## 🚀 Features

- 🔐 User Login System  
- 👤 User Registration  
- 🗂️ Topic Management UI (basic structure)  
- 🧠 Quiz platform foundation (extendable)  

---

## 🛠️ Technologies Used

- **Java (Swing)** – GUI development  
- **MySQL** – Database  
- **JDBC** – Database connectivity  
- **NetBeans IDE** – Development environment  

---

## 📂 Project Structure


E-Learning Quiz Platform (Java + MySQL)/
│
├── Quiz_Platform.java # Main entry point
├── login.java # Login form & authentication
├── Users.java # User registration
├── Topics.java # Topic management UI
├── *.form # NetBeans GUI design files


---

## 🗄️ Database Setup

### Create database:
```sql
CREATE DATABASE quiz_platform;
Create users table:
CREATE TABLE users (
    username VARCHAR(50) PRIMARY KEY,
    password VARCHAR(50)
);
Update database credentials in code:
String url = "jdbc:mysql://localhost:3306/quiz_platform";
String user = "root";
String password = "your_password";
▶️ How to Run
Open the project in NetBeans
Ensure MySQL server is running
Add MySQL Connector/J (JDBC driver)
Run:
Quiz_Platform.java
⚠️ Known Issues
Passwords are stored in plain text (not secure)
Topic & question features are incomplete
No quiz logic implemented yet
Hardcoded database credentials
Limited validation and error handling
🔮 Future Improvements
🔒 Password hashing (e.g., BCrypt)
🧠 Full quiz system (questions, scoring, results)
📊 Admin dashboard
🧾 Database schema expansion
🌐 Web version (Spring Boot / React)
🧪 Input validation & exception handling
