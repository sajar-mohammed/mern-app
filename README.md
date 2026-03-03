# 🚀 MERN Stack Full-Stack Application

A full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

This project demonstrates end-to-end application development including API creation, database integration, and frontend-backend communication.

---

## 📌 Project Overview

This application follows a typical MERN architecture:

- React frontend (Vite-based setup)
- Node.js + Express backend
- MongoDB database
- RESTful API communication

The goal of this project was to practice building and connecting a full-stack application with proper folder separation and API structure.

---

## 🛠 Tech Stack

### Frontend (Client)
- React.js
- Vite
- JavaScript (ES6+)
- CSS

### Backend (Server)
- Node.js
- Express.js
- MongoDB
- Mongoose

---

## 📂 Project Structure


mern-app/
│
├── client/ # React frontend
│ ├── src/
│ ├── public/
│ ├── package.json
│ └── vite.config.js
│
├── server/ # Express backend
│ ├── models/
│ ├── index.js
│ ├── package.json
│ └── .env
│
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/sajar-mohammed/mern-app.git
cd mern-app
2️⃣ Setup Backend
cd server
npm install

Create a .env file inside /server:

PORT=5000
MONGO_URI=your_mongodb_connection_string

Start backend server:

npm start
3️⃣ Setup Frontend

Open new terminal:

cd client
npm install
npm run dev

Frontend runs on:

http://localhost:5173

Backend runs on:

http://localhost:5000
🔗 API Communication

The frontend communicates with backend using REST APIs.

Typical flow:

React makes HTTP request

Express handles route

Mongoose interacts with MongoDB

JSON response returned to client

🎯 Features

Full-stack architecture

REST API development

MongoDB database integration

Component-based frontend structure

Environment variable configuration

Separate client and server modules

🧠 What I Practiced

Building RESTful APIs with Express

Structuring backend with models and routes

Connecting frontend to backend

Managing environment variables securely

Handling asynchronous database operations

Full-stack debugging and testing

🔮 Future Improvements

Add authentication (JWT)

Add role-based authorization

Add validation middleware

Add pagination and filtering

Deploy backend to cloud (GCP / AWS)

Deploy frontend to Vercel / Netlify

Add Docker support
