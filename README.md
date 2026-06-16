# Cake Management System

## 📌 About

**Cake Management System** is a Java-based desktop application with **MySQL database integration** designed to automate bakery operations. It provides a GUI for both administrators and customers, enabling efficient management of cake inventory, orders, payments, and deliveries with persistent data storage.

---

## ✨ Features

### Customer
- Sign up & login
- Browse cake menu
- Place, track & cancel orders
- Payment options (EasyPaisa, JazzCash, COD)
- Submit feedback & ratings

### Admin
- Customer management (CRUD)
- Catalog management (CRUD)
- Order management (CRUD)
- Financial reporting
- Delivery personnel management

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Java |
| Database | MySQL |
| GUI | Java Swing |
| JDBC | MySQL Connector/J |

---

## 🚀 Quick Start

```bash
# Import database
mysql -u root -p < cake_db.sql

# Compile
javac -cp ".;mysql-connector-java-8.0.28.jar" *.java

# Run
java -cp ".;mysql-connector-java-8.0.28.jar" CakeManagementSystem
```

---

## 📊 Database Schema

| Table | Purpose |
|-------|---------|
| `customer` | Customer information |
| `cake` | Cake inventory |
| `customerorder` | Order records |
| `customerpayment` | Payment transactions |
| `customerdeliveryadress` | Delivery details |
| `deliverypersonal` | Delivery personnel |
| `adminorder` | Admin order management |

---

## 👤 Developer

**Simaab Malik** (SAP ID: 54910)  
BS Software Engineering  
Riphah International University  
**Supervisor**: Ma'am Seemab  
**Semester**: 4th Sem

**Session**: Spring 2025

---

## 📄 License

Educational Project - Database Integrated Cake Management System

---

## 🔄 Version History

| Version | Course | Storage | Interface |
|---------|--------|---------|-----------|
| v1.0 | OOP | Collections (ArrayList) | Console |
| v2.0 | Database Integrated | MySQL | Swing GUI |

---

*For complete details, refer to the project proposal.*
