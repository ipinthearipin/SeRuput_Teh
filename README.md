
# ☕ SeRuput_Teh - A Simple Java E-Commerce Desktop App

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

> A desktop-based e-commerce application built using Java (Swing + JDBC), implementing login/register, product management, cart, and transaction features. Designed with MVC pattern.

---

## 📦 Features

- 🔐 User Authentication (Login & Register)
- 🧑‍💼 Role-Based Navigation (Admin / Customer)
- 🛒 Product browsing, add to cart, checkout
- 📜 Transaction History (Customer)
- 🧑‍🍳 Admin Product Management (CRUD)
- 💾 Database connection using JDBC

---

## 🧭 Project Structure

```
SeRuput_Teh/
├── src/
│   ├── main/                  # Main.java (App entry point)
│   ├── component/             # Navigation bars
│   ├── models/                # Data classes: User, Product, TransactionHeader
│   ├── pages/                 # UI Pages: Login, Register, Cart, History, Home, etc.
│   └── util/                  # Connect.java (Database connection)
├── bin/                       # Compiled class files
├── .classpath, .project       # Eclipse project configs
├── module-info.java           # Java module declaration (Java 9+)
README.md                  # Project description
```

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 11 or newer
- MySQL or SQLite database
- Java IDE (Eclipse / IntelliJ recommended)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/ipinthearipin/SeRuput_Teh.git
cd SeRuput_Teh
```

2. Open project in Eclipse or IntelliJ

3. Configure database in `src/util/Connect.java`

4. Run `Main.java` to start the application

---

## 🧠 Tech Stack

- Java SE (11+)
- Swing (GUI)
- JDBC (Database)
- MVC Design Pattern

---

## 📌 Notes

- Passwords are stored in plain text
- SQL injection prevention is not implemented
- Future improvement: JavaFX / Spring Boot REST API + Web Frontend

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


## 👨‍💻 Author

Made with ☕ by Muhammad Faza Arifin  

---
