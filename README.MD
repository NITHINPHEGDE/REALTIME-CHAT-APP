<h1 align="center">💬 Chatify — Real-Time Full-Stack Chat Application</h1>

<p align="center">
  <b>Secure • Real-time • Scalable • Modern UI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/Backend-Node.js-green" />
  <img src="https://img.shields.io/badge/Frontend-React-blue" />
  <img src="https://img.shields.io/badge/Database-MongoDB-brightgreen" />
  <img src="https://img.shields.io/badge/Real--Time-Socket.io-black" />
</p>

<p align="center">
  <img src="/frontend/public/screenshot-for-readme.png" alt="Chatify Demo" />
</p>

---

## 🚀 About the Project

**Chatify** is a modern **full-stack real-time chat application** built with performance, security, and user experience in mind.  
It supports **JWT authentication**, **real-time messaging**, **email automation**, and a **beautiful responsive UI**.

---

## ✨ Key Features

- 🔐 Custom JWT Authentication (No 3rd-party auth)
- ⚡ Real-Time Messaging using Socket.io
- 🟢 Live Online / Offline Presence
- 🔔 Typing & Notification Sounds (Toggle supported)
- 📨 Automated Welcome Emails (Resend)
- 🗂️ Image Uploads via Cloudinary
- 🚦 API Rate Limiting with Arcjet
- 🧰 RESTful API with Node.js & Express
- 🧱 MongoDB for persistent data storage
- 🎨 Modern UI with React, Tailwind CSS & DaisyUI
- 🧠 Zustand for global state management
- 🚀 Production-ready (Free-tier friendly)

---

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- DaisyUI
- Zustand
- Socket.io Client

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- Arcjet
- Cloudinary
- Resend

---

## 🧪 Environment Variables

### 📂 Backend (`/backend/.env`)

```env
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development

---

## ▶️ Running the Application

###🔧 Start Backend Server

```env
cd backend
npm install
npm run dev

---

###💻 Start Frontend Client

```env
cd frontend
npm install
npm run dev


