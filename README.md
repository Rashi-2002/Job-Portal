# 🏢 Job Portal - Full Stack Web Application

A **Full-Stack Job Portal** built using **ReactJS, Node.js, Express, and MongoDB**. This application allows users to **register, post jobs, apply for jobs, and manage applications** with a user-friendly interface and **admin dashboard**.

📂 **GitHub Repo:** [Job-Portal](https://github.com/Rashi-2002/Job-Portal)  

---

## 📌 Features  
✔️ User Authentication (Job Seekers & Recruiters)  
✔️ Job Posting and Application System  
✔️ Profile Management with File Uploads (Multer)  
✔️ Admin Dashboard to Manage Jobs & Applicants  
✔️ Job Filtering & Search Functionality  
✔️ Redux Toolkit for State Management  
✔️ Secure JWT Authentication  
✔️ Responsive UI with Shadcn UI  
✔️ Smooth Animations using Framer Motion  

---

## 🛠 Tech Stack  

| Frontend        | Backend        | Database | Other |
|----------------|---------------|------------|------------|
| ReactJS (Vite) | Node.js       | MongoDB     | Redux Toolkit |
| Shadcn UI      | Express.js    | Mongoose    | Multer (File Uploads) |
| Framer Motion  | JWT Auth      | Bcrypt.js   | Axios  |

---

## 📂 Folder Structure  

job-portal/
│── backend/                 # Node.js + Express Backend
│   ├── models/              # Database Schemas
│   ├── routes/              # API Routes
│   ├── controllers/         # Business Logic
│   ├── middleware/          # Authentication & Authorization
│   ├── config/              # Database Connection
│   ├── uploads/             # File Uploads
│   ├── server.js            # Main Server File
│   ├── .env                 # Environment Variables
│   ├── package.json         # Backend Dependencies
│
│── frontend/                # ReactJS Frontend
│   ├── src/                 
│   │   ├── components/      # Reusable UI Components
│   │   ├── pages/           # Pages like Home, Login, Profile
│   │   ├── redux/           # State Management (Redux Toolkit)
│   │   ├── services/        # API Calls
│   │   ├── assets/          # Images, Icons, etc.
│   │   ├── App.js           # Main App Component
│   │   └── index.js         # Entry Point
│   ├── public/              # Static Files
│   ├── .env                 # Environment Variables
│   ├── package.json         # Frontend Dependencies
│
│── .gitignore               # Files to Ignore in Version Control
│── README.md                # Project Documentation
│── package.json             # Project Dependencies
