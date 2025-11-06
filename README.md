# SmartResume - AI Resume Assistant 🚀

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

### 🌐 Live Demo

**[SmartResume](https://smartresume-app.netlify.app/)**

---

### 📋 Table of Contents

1.  [About The Project](#-about-the-project)
2.  [Key Features](#-key-features)
3.  [Tech Stack](#️-tech-stack)
4.  [Environment Variables](#-environment-variables)
---

### 📖 About The Project

SmartResume is a full-stack MERN application designed to help job seekers gain a competitive edge. Traditional resume writing is often a guessing game. This tool removes the guesswork by leveraging AI to provide objective, actionable feedback and helps users perfectly align their resume with the specific requirements of a job posting.

---

### ✨ Key Features

* **Secure User Authentication:** JWT-based login and registration to keep user data private.
* **AI-Powered Resume Analysis:** Upload a resume to receive a detailed score, breakdown, and a list of pros and cons.
* **AI-Powered Resume Customization:** Paste a job description to have the AI rewrite and tailor your resume, highlighting relevant keywords and skills.
* **Personal Profile & History:** A user dashboard to view all past analysis and customization activities.
* **Professional & Responsive UI:** A clean, modern interface built with Tailwind CSS that works beautifully on all devices.

---

### 🛠️ Tech Stack

This project is built with a modern MERN stack and other leading technologies.

| Frontend | Backend | Database | AI / Auth |
| :--- | :--- | :--- | :--- |
| **React** (Vite) | **Node.js** | **MongoDB** | **OpenRouter API** |
| **Tailwind CSS** | **Express.js** | **Mongoose** | **JWT & bcrypt.js** |
| **React Router** | | | |
| **Axios** | | | |

---

### 🔑 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` files.

#### `server/.env`
```env
# The port for the Express server
PORT=8080

# Your MongoDB connection string
MONGO_URI=your_mongodb_connection_string

# A secret key for signing JSON Web Tokens
JWT_SECRET=your_super_secret_jwt_key

# Your API key from OpenRouter.ai
OPENROUTER_API_KEY=your_openrouter_api_key
