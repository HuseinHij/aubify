# 📚 Aubify – AUB's Reddit-Style Q&A Platform

Aubify is a social network built specifically for AUB students. Inspired by Reddit, it allows students to ask and answer academic questions, upvote/downvote posts, comment, and engage with their university community in a focused and intuitive way.

---

## 🚀 Features

- 🧠 Ask and answer questions on any course or university topic
- 👍 Upvote/downvote posts and comments
- 💬 Threaded comment discussions
- 🔍 Search and filter by tags or popularity
- 👨‍🎓 Authentication system for AUB students
- 📱 Clean and responsive user interface

---

## 🛠️ Tech Stack

| Layer     | Technologies Used                                  |
|-----------|----------------------------------------------------|
| Frontend  | React, HTML5, CSS3, JavaScript                     |
| Backend   | Node.js, Express.js                                |
| Database  | MongoDB (Mongoose)                                 |
| Tools     | Git, GitHub, Postman, Visual Studio Code           |

---

## 📁 Folder Structure

```
aubify/
├── frontend/       # React application
├── backend/        # Node.js + Express server
└── README.md
```

---

## 🌐 Live Demo

You can try Aubify online:

🔗 **[Live Link](https://aubify.netlify.app)**

> 📌 Use the following test credentials to log in (will be added soon):

```
Username: [coming soon]
Password: [coming soon]
```

---

## 🧪 Getting Started (Run Locally)

To run the project locally, you'll need to start both the frontend and backend.

### ⚙️ Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- Git

---

### 🔧 Backend Setup

```bash
cd backend
npm install
```

1. Create a `.env` file in the `backend/` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

2. Start the backend server:

```bash
npm start
```

---

### 🎨 Frontend Setup

```bash
cd frontend
npm install
npm start
```

The frontend will run on `http://localhost:3000/`, and the backend will run on `http://localhost:5000/`.

---