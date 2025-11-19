# Ecommerce Microservices Showcase 🛒

## Introduction 💻
This project demonstrates a modern **e-commerce backend and frontend architecture**. The backend is composed of microservices for **products, orders, and user management**, while the frontend is a **React Native mobile app** supporting Apple and Google login with secure JWT authentication.  

The full source code is private; this repository showcases the architecture, key features, and implementation highlights.🙇🏻‍♂️

## Features 🔥
### Backend Microservices
- **User Management**
  - Register, login, and manage users
  - Secure endpoints using **JWT authentication**
- **Products Service**
  - CRUD operations for products
  - Optimized for frequent-access using **Redis caching**
- **Orders Service**
  - Create, update, and query orders
  - Integrates asynchronously with products and users via **WebClient**
- **Security**
  - **Secure path routing** using `SecurityChainFilter`
  - Role-based access control
- **Performance**
  - **Redis caching** for fast retrieval of products and cart items
  - Enhanced **user session management**  

### Frontend
- Built with **React Native**
- Supports **Apple and Google login**
- **JWT-secured authentication**
- Seamless interaction with backend microservices

### Integration & Communication
- Microservices communicate asynchronously using **Spring WebClient**
- Robust **error handling and response management**
- Extensible architecture for future microservices

### Developer Tools
- **Dockerized** services for easy local development
- API documentation and testing via **Swagger UI**
- Supports switching backend storage and caching configurations  

## Architecture 🎪
- **Backend:** Spring Boot REST APIs with JWT security and Redis caching  
- **Frontend:** React Native mobile app with OAuth login options  
- **Microservice Communication:** WebClient for asynchronous inter-service calls  
- **Caching:** Redis for frequently accessed data (products, cart, user sessions)  

### Architecture Diagram 🏛️
<p align="center">
  <img src="/Architecture.png" alt="architecture" width="100%" />
</p>

## Demonstration 🧪
<p align="center">
  <img src="/demo_1.jpg" alt="demo1" width="45%" />
  <img src="/demo_2.jpg" alt="demo2" width="45%" />
</p>

## Key Takeaways 🚀
- Built scalable **microservices architecture** for e-commerce  
- Implemented **secure and performant backend** with JWT and Redis caching  
- Developed **mobile-first frontend** with social login and session management  
- Integrated services efficiently using **WebClient** for asynchronous calls  
- Dockerized environment enables quick testing and deployment  
