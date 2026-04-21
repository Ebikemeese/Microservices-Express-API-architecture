# 🚀 Microservices Blog API (Express.js)

A scalable Express.js microservices API for a blogging platform, featuring Post, Identity (auth), Search, and Media services, powered by RabbitMQ, Redis, Cloudinary, Docker, and GitHub Actions.

---

## 🧩 Architecture

This project follows a microservices architecture with four core services:

- 📝 **Post Service** – Handles blog creation, updates, and publishing  
- 🔐 **Identity Service** – Manages users, authentication, and authorization  
- 🔍 **Search Service** – Provides fast and efficient content search  
- 🖼️ **Media Service** – Handles file uploads and media storage via Cloudinary  

---

## ⚙️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Messaging:** RabbitMQ (event-driven communication)  
- **Caching:** Redis  
- **Media Storage:** Cloudinary  
- **Containerization:** Docker & Docker Compose  
- **CI/CD:** GitHub Actions  

---

## 🔄 System Design Highlights

- Event-driven architecture using RabbitMQ  
- Stateless services for easy scaling  
- Centralized caching with Redis  
- Media handling via Cloudinary CDN  
- Fully containerized services using Docker  
- Automated workflows with GitHub Actions  

---
