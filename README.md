# Spring Security JWT Demo

A simple Spring Boot backend project demonstrating **JWT-based authentication and authorization** using **Spring Security**.  
This project was built for learning and testing purposes and is tested using **Postman**.

---

## 🚀 Features

- User authentication using **JWT (JSON Web Tokens)**
- Stateless security with **Spring Security**
- Custom JWT filter for request validation
- Secure REST APIs 
- Password encryption using **BCrypt**
- Clean layered architecture (Controller, Service, Repository)
- Tested using **Postman**

---

## 🛠 Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT
- Maven
- PostgreSQL
- JPA

---

## 🔐 Authentication Flow

1. User sends credentials to the authentication endpoint.
2. Credentials are validated using Spring Security.
3. On successful authentication, a **JWT token** is generated.
4. Client sends the token in the `Authorization` header for secured requests.
5. JWT filter validates the token on every request.

---

## 🧪 Testing

All endpoints were tested using **Postman** by:
- Sending login credentials
- Extracting JWT token
- Passing token in `Authorization: Bearer <token>` header

---

## 🎯 Purpose

This project was created to:
- Understand **Spring Security internals**
- Learn **JWT authentication flow**
- Practice building **secure REST APIs**

---

## 🧠 Learnings

- How Spring Security authentication works internally
- Implementing stateless authentication using JWT
- Writing custom security filters
- Structuring backend applications properly

## 📜 License

This project is for educational purposes.