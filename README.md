🏦 Online Banking System

📌 Project Overview

The Online Banking System is a web-based application developed to provide basic banking services through an easy-to-use and responsive interface. The system allows users to securely access their accounts and perform common banking operations such as checking account balance, viewing transactions, transferring money, and managing account details.

The project is developed using HTML, CSS, JavaScript, and Bootstrap for the frontend. It can be integrated with Java/JDBC and MySQL for backend and database operations.

---

🎯 Objectives

- Provide a simple and user-friendly online banking interface.
- Allow customers to view their account information.
- Enable secure money transfer between accounts.
- Display transaction history.
- Provide a responsive design for desktop and mobile devices.
- Reduce the need for manual banking operations.

---

🛠️ Technologies Used

Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap 5

Backend

- Java
- JDBC

Database

- MySQL

Development Tools

- Eclipse / IntelliJ IDEA
- Visual Studio Code
- MySQL Workbench
- Git & GitHub

---

✨ Features

👤 Customer Features

- User Registration
- User Login
- Dashboard
- View Account Details
- Check Account Balance
- Money Transfer
- Deposit and Withdrawal
- Transaction History
- Profile Management
- Logout

🔐 Security Features

- Login authentication
- Password validation
- Session management
- Input validation
- Secure database connectivity

---

🏗️ System Architecture

The project follows a Layered Architecture:

┌───────────────────────────┐
│       Presentation        │
│    HTML / CSS / JS /      │
│        Bootstrap          │
└─────────────┬─────────────┘
              ↓
┌───────────────────────────┐
│      Service Layer        │
│    Business Logic         │
└─────────────┬─────────────┘
              ↓
┌───────────────────────────┐
│        DAO Layer           │
│    Database Operations     │
└─────────────┬─────────────┘
              ↓
┌───────────────────────────┐
│       Database Layer       │
│          MySQL             │
└───────────────────────────┘

---

📂 Project Structure

OnlineBankingSystem/
│
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── transfer.html
├── transactions.html
├── profile.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   └── logo.png
│
└── README.md

Java Backend Structure

src/
│
├── model/
│   ├── Customer.java
│   ├── Account.java
│   └── Transaction.java
│
├── dao/
│   ├── CustomerDAO.java
│   ├── AccountDAO.java
│   └── TransactionDAO.java
│
├── service/
│   ├── LoginService.java
│   └── BankingService.java
│
├── util/
│   └── DBConnection.java
│
└── main/
    └── BankingApp.java

---

💻 Main Modules

1. Login Module

Allows registered customers to securely log in using their credentials.

2. Registration Module

Allows new customers to create an account by providing the required information.

3. Dashboard Module

Displays account balance, customer information, and available banking services.

4. Fund Transfer Module

Allows customers to transfer money from one account to another.

5. Transaction Module

Maintains and displays the customer's transaction history.

6. Profile Module

Allows customers to view and update their personal information.

---

🗄️ Database Tables

The MySQL database can contain the following tables:

Customer

Column| Description
customer_id| Unique customer ID
name| Customer name
email| Customer email
phone| Phone number
password| Login password

Account

Column| Description
account_id| Unique account ID
customer_id| Customer reference
account_type| Type of account
balance| Current balance

Transaction

Column| Description
transaction_id| Unique transaction ID
account_id| Account reference
transaction_type| Deposit/Withdrawal/Transfer
amount| Transaction amount
transaction_date| Date of transaction

---

🚀 How to Run the Project

1. Download or clone the project.
2. Open the project in Visual Studio Code or Eclipse.
3. Open the frontend files in a browser.
4. Configure the MySQL database.
5. Create the required database tables.
6. Configure JDBC database connection.
7. Run the Java backend.
8. Open the application and use the login/registration pages.

---

🔮 Future Enhancements

- OTP-based authentication
- Email/SMS transaction notifications
- QR-code payments
- Online bill payment
- Loan management
- Credit card management
- AI-based financial assistance
- Mobile application integration
- Two-factor authentication

---

👨‍💻 Project Purpose

This project is developed as an academic/final-year project to demonstrate web development, Java programming, JDBC connectivity, database management, and layered software architecture.

---

📄 License

This project is developed for educational purposes.



Author
Ilakya
