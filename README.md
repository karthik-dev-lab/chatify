# Chatify 💬

A full-stack real-time chat application built with React, Node.js, Express, MongoDB, Socket.IO, Zustand, and Cloudinary.

## 🚀 Features

* 🔐 JWT Authentication
* 👤 User Signup & Login
* 🖼️ Profile Picture Upload
* 💬 Real-Time Messaging with Socket.IO
* 🟢 Online/Offline User Status
* 📷 Image Sharing in Chat
* 🔔 Notification Sounds
* 🎵 Typing Sounds Toggle
* ☁️ Cloudinary Image Storage
* 📧 Welcome Emails using Resend
* 🚦 API Rate Limiting & Security with Arcjet
* 🎨 Responsive UI with Tailwind CSS & DaisyUI
* ⚡ Zustand State Management
* 🌐 Production Deployment on Render

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* React Router
* Zustand
* Axios
* Tailwind CSS
* DaisyUI
* Socket.IO Client
* React Hot Toast

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Socket.IO
* Cloudinary
* Resend
* Arcjet

---

## 📁 Project Structure

```bash
chatify-app/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── lib/
│   │   └── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── hooks/
│   │   └── lib/
│   └── package.json
│
└── package.json
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the `backend` directory:

```env
PORT=3000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLIENT_URL=http://localhost:5173

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_verified_sender_email
EMAIL_FROM_NAME=Chatify

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development

NODE_ENV=development
```

---

## 🏃 Local Setup

### Clone Repository

```bash
git clone https://github.com/your-username/chatify.git
cd chatify
```

### Install Dependencies

```bash
npm install --prefix backend
npm install --prefix frontend
```

### Run Backend

```bash
cd backend
npm run dev
```

### Run Frontend

```bash
cd frontend
npm run dev
```

Frontend:

```bash
http://localhost:5173
```

Backend:

```bash
http://localhost:3000
```

---

## 🔌 Socket.IO Workflow

```text
User Login
    ↓
Socket Connection
    ↓
JWT Authentication
    ↓
User Added to Online Users Map
    ↓
Online Users Broadcasted
    ↓
Real-Time Messaging
    ↓
Message Delivered Instantly
```

---

## 📸 Screenshots

Add screenshots here:

* Login Page
* Signup Page
* Chat Interface
* Profile Management

---

## 🚀 Deployment

This project is deployed on Render.

### Build Command

```bash
npm run build
```

### Start Command

```bash
npm start
```

---

## 🔒 Security Features

* HTTP-only JWT Cookies
* Password Hashing with bcrypt
* Arcjet Rate Limiting
* Bot Detection
* Protected Routes
* Secure Socket Authentication

---

## 📚 Learning Outcomes

Through this project I gained hands-on experience with:

* Authentication & Authorization
* REST APIs
* MongoDB & Mongoose
* Real-Time Communication
* State Management with Zustand
* Image Upload Workflows
* Deployment & Production Debugging
* Full-Stack Application Architecture

---

## 🙌 Acknowledgements

Inspired by the excellent tutorial by Codesistency.

---

## 📄 License

This project is licensed under the MIT License.

Feel free to fork, modify, and use it for learning purposes.
