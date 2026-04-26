# 🛒 Luv2Code E-Commerce Application

A full-stack **E-Commerce Shopping Cart application** built using **Spring Boot (backend)** and **Angular (frontend)** with enterprise-level features like security, payment processing, and cloud-ready architecture.

---

## 🚀 Project Objectives

- Develop a full-stack E-Commerce Shopping Cart application
- Build frontend using **Angular** and backend using **Spring Boot**
- Secure application using **JWT, OAuth2, and OpenID Connect (Okta)**
- Enable secure communication using **TLS/SSL (HTTPS)**
- Integrate **Stripe API** for payment processing

---

## 🧩 Tech Stack

### Frontend

- Angular
- TypeScript
- Bootstrap / ng-bootstrap
- RxJS
- Stripe.js

### Backend

- Spring Boot
- Spring Data JPA
- Spring Security
- REST APIs
- Okta Authentication
- Stripe API Integration

### Database

- MySQL (Country / State / Orders / Products)

---

## 🛍️ Features (Release Plan)

### 🔹 Release 1.0

- Product listing
- Category-based browsing
- Search functionality

### 🔹 Release 2.0

- Online shop template integration
- Product search (text-based)
- Product details (master/detail view)
- Pagination support
- Shopping cart (CRUD)
- Checkout system

### 🔹 Release 3.0

- User authentication (Login/Logout)
- OAuth2 / OpenID Connect (Okta)
- VIP protected routes
- Order history tracking

---

## 🛒 Shopping Cart Features

- Add / remove products
- Increment quantity
- Real-time cart updates
- Cart persistence using session storage
- Total price & quantity calculation
- Cart details page

---

## 🧾 Checkout System

- Reactive forms implementation
- Form validation (required fields, email, etc.)
- Credit card form integration
- Country & state dropdown (dynamic loading)
- Order submission workflow

---

## 🔐 Security Features

- Okta authentication (OAuth2 / OpenID Connect)
- JWT-based API protection
- Route guards for protected pages
- Secure backend endpoints
- HTTPS communication (TLS/SSL)

---

## 💳 Payment Integration

- Stripe PaymentIntent API
- Credit/Debit card payments
- Stripe Elements UI integration
- Email receipt support
- Secure transaction handling

---

## 🧠 Key Concepts Used

- Angular Reactive Forms
- RxJS Subjects & BehaviorSubject
- REST API integration
- Spring Boot REST architecture
- CORS configuration
- Angular Interceptors
- Web Storage API (Session Storage)
- Custom validators
- Route Guards

---

## 📦 Database Design

### Tables

- country
- state
- customer
- orders
- order_items
- address

### Relationships

- Country → States (One-to-Many)
- Orders → OrderItems (One-to-Many)
- Customer → Orders (One-to-Many)

---

## ⚙️ Setup Instructions

### Backend (Spring Boot)

```bash
mvn clean install
mvn spring-boot:run
```

### Frontend (Angular)

```bash
npm install
npm start
```

Run with environment:

```bash
npm start -- --configuration=qa
```

---

## 🔑 Environment Configuration

- Angular environments support (dev / qa / prod)
- Stripe publishable key stored in environment files
- Okta client ID + issuer configuration
- Backend API URL centralized

---

## 💳 Stripe Test Cards

| Card Number         | Result               |
| ------------------- | -------------------- |
| 4242 4242 4242 4242 | Success              |
| 4000 0000 0000 0002 | Card Declined        |
| 4000 0000 0000 9995 | Insufficient Balance |

---

## 🔒 Security Notes

- API secured using Spring Security + Okta
- Authorization header:

  ```
  Bearer <token>
  ```

- HTTPS enabled using self-signed certificates
- CSRF disabled for stateless API

---

## 📈 Future Improvements

- Docker containerization
- Kubernetes deployment
- Microservices architecture split
- Admin dashboard
- Product recommendation engine

---

## ⭐ Project Status

✔ Backend Complete  
✔ Frontend Complete  
✔ Security Integrated  
✔ Payment System Integrated  
✔ Production-ready Architecture  

---
