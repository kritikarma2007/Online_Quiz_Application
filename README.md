# Online Quiz Application

## Overview

Online Quiz Application is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that enables users to securely register, log in, attempt timed multiple-choice quizzes, and instantly view their scores. The application follows a client-server architecture with a React frontend, Express backend, and MongoDB database.

---

# Features

- Secure user authentication using JWT and bcryptjs
- Timed multiple-choice quiz interface
- Pre-quiz instructions before starting the test
- Automatic score calculation and result summary
- Responsive design for desktop, tablet, and mobile devices
- RESTful API architecture

---

# Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT
- bcryptjs

---

# System Architecture

```
React Client
      │
      │ REST API
      ▼
Express Server
      │
      ▼
MongoDB Database
```

---

# Project Structure

```
Online_QuizApplication/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Online_QuizApplication.git
cd Online_QuizApplication
```

## Install Dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd ../server
npm install
```

---

# Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

# Run the Application

Start Backend

```bash
cd server
npm start
```

Start Frontend

```bash
cd client
npm start
```

Frontend: `http://localhost:3000`

Backend: `http://localhost:5000`

---

# Workflow

```
Register/Login
      │
      ▼
Read Instructions
      │
      ▼
Attempt Timed Quiz
      │
      ▼
Submit Answers
      │
      ▼
View Results
```

---

# Future Enhancements

- Admin Dashboard
- Quiz Categories
- Leaderboard
- Quiz History
- Email Verification
- Performance Analytics

---

# License

This project is developed for educational and learning purposes.
