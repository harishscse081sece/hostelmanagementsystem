# 🏠 Hostel Management System

A full-stack web application to manage hostel operations including mess menu, complaints, and user authentication.

🔗 **Live Demo**: [Click Here](frontendhostelmanage-git-main-harish-ss-projects-85e28866.vercel.app)

---

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

---

## ✨ Features

- 🔐 Role-based authentication (Student / Admin)
- 🍽️ Weekly mess menu management
- 📋 Complaint submission and tracking system
- ✅ Admin can mark complaints as Solved
- 👤 User profile view
- 📱 Responsive UI

---

## 🔑 Test Credentials

| Role    | Email                | Phone      | Password   |
|---------|----------------------|------------|------------|
| Admin   | admin@hostel.com     | 7200999142 | admin123   |
| Student | rahul@student.com    | 9876543210 | student123 |

---

## 📁 Repositories

| Part     | Repository |
|----------|------------|
| Frontend | [hostelmanagefrontend](https://github.com/harishscse081sece/hostelmanagefrontend) |
| Backend  | [backendhostelmanage](https://github.com/harishscse081sece/backendhostelmanage) |

---

## 🚀 Deployment

| Service  | Platform      | URL |
|----------|---------------|-----|
| Frontend | Vercel        | [Live](https://hostelmanagefrontend-git-main-harish-ss-projects-85e28866.vercel.app) |
| Backend  | Render        | [API](https://hostel-management-backend-bukg.onrender.com) |
| Database | MongoDB Atlas | Cloud Hosted |

---

## 📌 API Endpoints

| Method | Endpoint              | Description              |
|--------|-----------------------|--------------------------|
| POST   | /auth/admin           | Register user            |
| POST   | /auth/student         | Login user               |
| GET    | /menu                 | Get weekly mess menu     |
| PUT    | /menu/:day            | Update menu (admin)      |
| GET    | /complaints           | Get complaints           |
| POST   | /complaints           | Submit complaint         |
| PUT    | /complaints/:id       | Update complaint status  |

---

## 👨‍💻 Author

**Harish S**
- GitHub: [@harishscse081sece](https://github.com/harishscse081sece)
