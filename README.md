# 🌐 Developer Social Network

## 🚀 Project Overview

a full-stack social networking application built using the MERN stack.  
The platform allows developers to create profiles, authenticate securely, share posts, and interact with other developers.

This project demonstrates authentication, protected routing, API integration, and scalable full-stack architecture.

---

## 🛠 Tech Stack

### Frontend
- React.js
- Redux (State Management)
- React Router v6
- Axios

### Backend
- Node.js
- Express.js
- JWT Authentication
- RESTful APIs

### Database
- MongoDB (Mongoose ODM)

---

## ✨ Key Features

- User Registration & Login (JWT Authentication)
- Protected Routes
- Developer Profile Creation
- Add Education & Experience
- Create, Like & Comment on Posts
- GitHub Repository Integration
- Token Expiration Handling (Auto Logout)
- Redux Store State Management
- Axios Interceptors for API Security

---

## 🗄 Database Structure

### Users Collection
- name
- email
- password (hashed)
- avatar
- createdAt

### Profiles Collection
- user (ObjectId reference)
- bio
- skills
- experience[]
- education[]
- social links

### Posts Collection
- user
- text
- likes[]
- comments[]
- createdAt

---

## 🔗 Frontend–Backend Integration

- REST APIs connect React frontend with Express backend.
- JWT token stored securely and attached to protected requests.
- Axios interceptor manages token expiration.
- Redux manages global state across the application.

---

## 📦 Installation

### Install Dependencies
```
npm install
cd client
npm install
```

### Run Development Server
```
npm run dev
```

---

## 🎯 What I Learned

- Implemented secure JWT-based authentication
- Built protected routing system
- Designed scalable MongoDB schemas
- Managed global state using Redux
- Integrated third-party APIs (GitHub)
- Handled API error management and token security

---

## 👩‍💻 Developed By

Sushmitha Linganaboina  
Full Stack Developer | React | Node.js | MongoDB | Open to Work

---

✨ Building secure and scalable full-stack web applications.
