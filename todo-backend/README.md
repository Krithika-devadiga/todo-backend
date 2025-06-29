# 🧠 Todo App Backend

This is the backend for a simple **To-Do List Web Application**, built with **Node.js**, **Express**, and **MongoDB (via Mongoose)**. It provides RESTful APIs for performing CRUD operations on todo tasks.

---

## 🔍 Key Features:

- Create, Read, Update, and Delete Todos
- Persistent storage using MongoDB
- Modular code structure with Express routes
- Environment-based MongoDB URI with `.env` config

---

## 📁 Project Structure:
todo-backend/
│
├── models/ # Mongoose schemas
│ └── Todo.js
│
├── routes/ # API route handlers
│ └── todoRoutes.js
│
├── server.js # Entry point
├── .env # Environment variables
├── package.json # Project metadata
└── README.md # Project documentation


---

## 🛠️ Tools & Technologies Used:

- 🟢 Node.js + Express.js  
- 🍃 MongoDB Atlas (via Mongoose)  
- 🌐 CORS for cross-origin support  
- 📦 dotenv for environment configuration  

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/todo-backend.git
cd todo-backend

2. Install dependencies
npm install


3. Configure .env file
PORT=5000
MONGO_URI=your-mongodb-uri-here

▶️ Run the Application
node server.js
You should see:
MongoDB Connected
Server running successfully on port 5000
