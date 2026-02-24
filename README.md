# 🚀 Local Service Provider Platform

A full-stack MERN application that connects users with trusted local service providers such as electricians, plumbers, tutors, mechanics, and more.

This platform allows users to discover services, book appointments, and manage service requests efficiently.

---

## 📌 Project Overview

The **Local Service Provider Platform** is designed to bridge the gap between customers and verified local professionals.

It provides:

- Easy service discovery
- Online booking system
- User authentication
- Provider dashboard
- Admin management

This project is developed as part of MCA Semester-2 academic work using the MERN Stack.

---

## 🛠️ Tech Stack

### 🔹 Frontend

- React.js
- JavaScript

### 🔹 Backend

- Node.js
- Express.js
- MongoDB

### 🔹 Development Tools

- Git & GitHub
- Nodemon

## 🏗️ Project Architecture

## 🏗️ Project Architecture

The application follows a standard MERN stack layered architecture:

Client (Frontend) → API Layer → Server (Backend) → Database (MongoDB)

---

### 🔹 1. Frontend Layer (React + Vite)

Responsible for:

- User Interface (UI)
- Handling user interactions
- Sending API requests to backend
- Managing global state

Main Structure:

client/
│
├── public/ # Static files
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Application pages (Home, Login, Dashboard)
│ ├── services/ # API calls using Axios/Fetch
│ ├── context/ # Global state management
│ ├── App.jsx # Root component
│ └── main.jsx # Entry point
└── package.json

---

### 🔹 2. Backend Layer (Node + Express)

Responsible for:

- Business logic
- Authentication & Authorization
- API route handling
- Database operations

Main Structure:

server/
│
├── config/
│ └── db.js # MongoDB connection setup
│
├── controllers/ # Business logic functions
│
├── models/ # Mongoose schemas
│
├── routes/ # API endpoints
│
├── middleware/ # Custom middleware (auth, error handling)
│
├── server.js # Main server entry point
└── package.json

---

### 🔹 3. Database Layer (MongoDB)

Responsible for:

- Storing users
- Storing service providers
- Managing bookings
- Handling reviews & ratings

Collections Example:

- users
- serviceProviders
- bookings
- reviews

---

### 🔹 Application Flow

1. User interacts with frontend.
2. Frontend sends request to backend API.
3. Backend processes request.
4. Backend communicates with MongoDB.
5. Response sent back to frontend.
6. UI updates dynamically.

---

### 🔹 Architecture Pattern Used

- MVC Pattern (Model-View-Controller)
  - Model → Database Schema
  - View → React Frontend
  - Controller → Business Logic
