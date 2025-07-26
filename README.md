# 📘 E-Learning Platform

A full-stack E-Learning web application tailored specifically for **Computer Science Engineering (CSE)** students. Built using the powerful **MERN Stack**, the platform offers seamless access to courses, lecture videos, assignments, quizzes, and peer discussion forums — all in one place.

> Empowering students to learn at their own pace, anytime and anywhere.

---

## 🧑‍💻 Built With

- **MongoDB** – NoSQL Database for storing user data, course content, assignments, and more.
- **Express.js** – Backend framework to handle APIs and routing.
- **React.js** – Modern front-end library for building dynamic UI.
- **Node.js** – Runtime environment for scalable backend services.

---

## 🌟 Key Features

### 👩‍🏫 For Students:
- 📚 Browse and enroll in CSE courses (e.g., DSA, OS, CN, DBMS, AI, ML)
- 🎥 Watch high-quality lecture videos
- 📝 Submit assignments & take quizzes
- 📈 Track progress and performance
- 🧑‍🤝‍🧑 Participate in discussion forums

### 👨‍🏫 For Instructors:
- ➕ Add/manage courses, modules, and video content
- 📝 Create quizzes and assignments with deadlines
- ✅ Grade submissions and publish feedback

### 🛡️ For Admin:
- 🔐 Manage users and roles (student/instructor/admin)
- 📊 Dashboard with platform usage statistics
- 🚫 Moderate discussion forums and reported content

---

## 🗂️ Folder Structure

cse-e-learning-platform/
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── assets/
│ ├── components/
│ ├── pages/
│ ├── context/
│ └── App.js
│
├── server/ # Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── server.js
│
├── .env
├── README.md
└── package.json

### 🔧 Prerequisites

- Node.js & npm
- MongoDB Atlas or local MongoDB
- Git

### 📥 Clone Repository

```bash
git clone https://github.com/ymishraaman05/elearning_webApp.git
cd elearning_webApp
🔐 Environment Variables
Create a .env file in the server/ directory with the following:

PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
🚀 Run the App
# Backend
cd server
npm install
npm run dev

# Frontend
cd ../client
npm install
npm start
App runs at: http://localhost:3000

📚 Course Modules (Sample)
Each course includes:

Overview

Lecture videos

Weekly assignments

Quizzes & MCQs

Final project (optional)

Example Courses:

Data Structures & Algorithms

Operating Systems

Computer Networks

DBMS

Machine Learning

Web Development

Compiler Design

🔐 Authentication & Authorization
JWT-based secure authentication

Role-based access: student, instructor, admin

Protected API routes and dashboard components

📡 API Overview
Method	Endpoint	Description
GET	/api/courses	Fetch all courses
POST	/api/auth/register	Register new user
POST	/api/auth/login	Login user
POST	/api/courses/:id/enroll	Enroll in course
GET	/api/assignments/:id	Get assignment
POST	/api/quizzes/submit	Submit quiz

Full API documentation available in /server/docs/api.md

🔄 Future Enhancements
💬 Live Chat with Instructor

📱 PWA support (offline mode)

🧾 Certificate Generation after course completion

📅 Calendar with deadlines and reminders

🔔 Email/Push Notifications

🧪 Testing
Unit Tests using Jest (backend) and React Testing Library (frontend)

# Run backend tests
cd server
npm test

# Run frontend tests
cd ../client
npm test
🌍 Live Demo
URL: https://github.com/mishraaman05/elearning_webApp/

🤝 Contributing
We welcome contributions! Here’s how:

Fork the repository

Create a new branch: git checkout -b feature-name

Make your changes and commit: git commit -m 'Add some feature'

Push the branch: git push origin feature-name
Create a Pull Request



👨‍💻 Developed By
Aman Mishra
💼 CSE Department | Passionate Developers
📧 mishraaman162002@gmail.com

