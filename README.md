
# 🍽️ Sanatan Food – Full Stack Food Ordering Platform

<p align="center">
  <img src="assets/sanatan-food-banner.png" alt="Sanatan Food Banner" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-Backend-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tailwind-CSS-38BDF8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JWT-Security-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=28&pause=1000&color=E91E63&center=true&vCenter=true&width=1000&lines=Sanatan+Food+🍽️;Full+Stack+Food+Ordering+Platform;Spring+Boot+%7C+React+%7C+MySQL;JWT+Security+%7C+Docker+%7C+Clean+Architecture;Production+Ready+Project" />
</p>

---

## 🚀 Project Overview

**Sanatan Food** is a **complete full‑stack food ordering and restaurant management platform** designed using **real‑world backend and frontend practices**.

This project is suitable for:
- ✅ Final year projects  
- ✅ Startup MVP  
- ✅ Portfolio / Resume  
- ✅ Real‑world backend learning  

It follows **clean architecture**, **role‑based access**, and is **production‑deploy ready**.

---

## 🌟 Key Highlights

✔ Full Stack Architecture (Frontend + Backend)  
✔ Role Based Access (Customer / Admin / Super Admin)  
✔ Secure JWT Authentication  
✔ RESTful APIs  
✔ Clean DTO-based communication  
✔ Docker & Docker‑Compose support  
✔ Scalable & Cloud‑ready  

---

## 🧠 System Architecture Flow

```text
┌──────────────┐
│ React UI     │
│ (Frontend)   │
└──────┬───────┘
       ↓
┌──────────────┐
│ REST APIs    │
│ Spring Boot  │
└──────┬───────┘
       ↓
┌──────────────┐
│ Service Layer│
│ Business     │
└──────┬───────┘
       ↓
┌──────────────┐
│ Repository   │
│ JPA/Hibernate│
└──────┬───────┘
       ↓
┌──────────────┐
│ MySQL DB     │
└──────────────┘
```

---

## 👥 User Roles & Permissions

### 👤 Customer
- Browse restaurants & menu
- Add items to cart
- Place orders
- Track order status

### 🧑‍🍳 Admin
- Manage restaurant
- Add / update food items
- View orders
- Update order status

### 👑 Super Admin
- Manage all users
- Platform‑level control
- Analytics & insights

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Security (JWT)
- Spring Data JPA
- Hibernate
- MySQL
- Maven

### Frontend
- React (Create React App)
- Tailwind CSS
- React Router
- Context / State Management
- Chart.js (Admin Analytics)

### DevOps
- Docker
- Docker Compose

---

## 📁 Backend Project Structure

```text
backend-spring-boot/
├── controller
├── service
├── repository
├── model
├── dto
├── request
├── response
├── exception
├── config
└── SanatanFoodApplication.java
```

---

## 📁 Frontend Project Structure

```text
src/
├── Admin
├── SuperAdmin
├── customers
├── Routers
├── State
├── config
├── theme
│   └── DarkTheme.js
├── App.js
└── index.js
```

---

## ⚙️ Local Setup

### Backend

```bash
git clone https://github.com/your-username/Sanatan-Food-Backend.git
cd backend
mvn spring-boot:run
```

Backend runs on:
```
http://localhost:8080
```

### Frontend

```bash
cd frontend
npm install
npm start
```

Frontend runs on:
```
http://localhost:3000
```

---

## 🔐 JWT Authentication Flow

```text
Login → JWT Token Generated → Stored on Client → Sent in Authorization Header
```

✔ Secure APIs  
✔ Role‑based access  
✔ Stateless authentication  

---

## 📦 Docker & Docker‑Compose

### Run Entire Project

```bash
docker-compose up --build
```

Services:
- Backend → 8080
- Frontend → 3000
- MySQL → 3306

---

## 📊 Admin Analytics Dashboard

- 📦 Total Orders
- 💰 Revenue Tracking
- 👥 User Growth
- 🍽 Most Ordered Items
- 📈 Graphical Charts

---

## 🛣 Roadmap

✔ Backend APIs  
✔ Frontend UI  
✔ JWT Security  
✔ Docker Setup  
⬜ Payment Gateway  
⬜ Cloud Deployment  
⬜ CI/CD Pipeline  
⬜ Microservices  

---

## 🤝 Contribution Guide

```bash
1. Fork Repository
2. Create Feature Branch
3. Commit Changes
4. Push to Branch
5. Open Pull Request
```

---

## 👨‍💻 Authors

### Keshav Upadhyay  
Backend Developer (Java & Spring Boot)

### Jyoti Singh  
Frontend Support / Collaborator

---

## 🌿 Vision

**Sanatan Food** aims to blend **modern technology with traditional values**, delivering a clean, scalable, and meaningful digital food platform.

---

⭐ If you like this project, don’t forget to **STAR ⭐ the repository**
