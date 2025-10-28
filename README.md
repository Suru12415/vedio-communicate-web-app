# 💻 Zoom Clone – Real-Time Video Conferencing App

A full-stack **Zoom Clone** web application built using **React.js**, **Node.js**, **Express**, and **MongoDB**.  
It enables users to **create/join video meetings**, **chat in real time**, and **share screens** – all from the browser.

---

## 🚀 Features

✅ User Authentication (JWT-based login/signup)  
✅ Create or Join Meetings instantly  
✅ Real-Time Video & Audio Communication (WebRTC + Socket.io)  
✅ Screen Sharing support  
✅ Chat Messaging within meeting rooms  
✅ Dynamic Meeting ID generation  
✅ Mute/Unmute and Camera Toggle  
✅ Modern UI with React.js  
✅ Fully responsive for mobile & desktop  
✅ MongoDB Atlas for user and meeting storage  
✅ Environment-based configuration with `.env`

---

## 🏗️ Tech Stack

**Frontend:**
- React.js  
- WebRTC  
- Socket.io-client  
- Axios  
- CSS3  

**Backend:**
- Node.js  
- Express.js  
- Socket.io  
- MongoDB + Mongoose  
- JWT Authentication  
- dotenv  

**Database:**
- MongoDB Atlas  

---

## 📁 Folder Structure

``` Zoom/
├── backend/
│ ├── src/
│ │ ├── app.js
│ │ ├── config/
│ │ │ └── db.js
│ │ ├── models/
│ │ │ └── User.js
│ │ ├── routes/
│ │ │ └── authRoutes.js
│ │ ├── controllers/
│ │ │ └── userController.js
│ │ └── utils/
│ ├── package.json
│ └── .env
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
│ ├── public/
│ ├── package.json
│ └── .env
│
└── README.md

```

---

## ⚙️ Setup Instructions

### 🔧 Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a .env file inside backend/ and add:
  ```bash
    
    MONGO_URI=mongodb+srv://<your-username>:<your-password>@cluster0.mongodb.net/zoom
    PORT=8000
   ```

4.Start the backend server:
  ```bash
    npm start
   ```
5.You should see:
 ```bash
   MONGO Connected DB Host: <your_host>
   LISTENING ON PORT 8000
   ```
### 🔧 frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
4.Start the frontend server:
  ```bash
    npm start
   ```
5.You should see:
   ```bash
   http://localhost:3000
   ```
