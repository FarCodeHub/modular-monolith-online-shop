# 🛒 Online Shop (Modular Monolith with DDD)

A sample e-commerce system designed using **Domain-Driven Design (DDD)** and a **modular monolith architecture**.

This project demonstrates how to structure a scalable and maintainable backend system by applying separation of concerns, clear boundaries between modules, and clean architectural principles.

---

## 🧠 Overview

The system is organized into multiple business modules, each representing a bounded context.
The goal of this project is to showcase a maintainable structure for growing applications without immediately moving to microservices.

---

## 🏗️ Architecture

The project follows a **modular monolith approach** combined with **DDD concepts**:

* Each module is isolated and has its own:

  * Application layer
  * Domain layer
  * Infrastructure layer

* Clear separation between:

  * Business logic
  * Application services
  * Data access

---

## 📦 Modules

* **Account Management** → User authentication and profile management
* **Shop Management** → Product catalog and shop operations
* **Inventory Management** → Stock and warehouse handling
* **Discount Management** → Pricing rules and discounts
* **Comment Management** → User comments and moderation
* **Blog Management** → Content and articles

---

## ⚙️ Technologies

* .NET Core / ASP.NET Core
* C#
* Entity Framework Core
* SQL Server
* HTML / CSS / JavaScript

---

## 🎯 Goals of This Project

* Demonstrate **DDD-based modular design**
* Show how to structure a **scalable monolithic application**
* Provide a reference for **clean separation of concerns**
* Serve as a foundation for future transition to microservices

---

## 🚀 How to Run

1. Clone the repository
2. Configure the database connection in `appsettings.json`
3. Run the application using Visual Studio or CLI:

```bash
dotnet run
```

---

## ⚠️ Notes

* This project focuses on **architecture and structure**, not UI completeness
* Some frontend parts are minimal and only included for demonstration purposes

---

## 📫 Contact

* LinkedIn: https://www.linkedin.com/in/farhadcodehub/
* GitHub: https://github.com/FarCodeHub

---

⭐️ If you are interested in backend architecture, modular systems, or DDD, feel free to explore the project.
