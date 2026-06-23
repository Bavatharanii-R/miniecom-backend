# 🛒 Mini E‑Commerce Backend

A simple Spring Boot + JPA backend for a mini e‑commerce application.  
This backend exposes REST APIs to manage products and integrates with a React frontend.

---

## 🚀 Features
- REST API for product listing (`GET /products`)
- Add new products (`POST /products`)
- JPA + Hibernate for database persistence
- PostgreSQL integration
- CORS enabled for React frontend (`http://localhost:3000`)

---

## 📂 Project Structure
```plaintext
src/
 ├── main/java/com/example/miniecom/
 │    ├── Product.java           # Entity class
 │    ├── ProductRepository.java # JPA repository
 │    └── ProductController.java # REST controller
 └── resources/
      ├── application.properties # DB config
      └── data.sql               # Sample products
```
⚙️ Tech Stack
Backend: Spring Boot

Database: PostgreSQL

ORM: JPA/Hibernate

🌐 Frontend Integration
This backend is designed to work with the React frontend:
👉 Mini E‑Commerce Frontend Repo (https://github.com/Bavatharanii-R/miniecom-frontend)
Build Tool: Maven
