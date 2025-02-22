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
│── backend/       # Node.js + Express Backend
│   ├── models/    # Database Schemas
│   ├── routes/    # API Routes
│   ├── controllers/ # Business Logic
│   ├── middleware/ # Authentication & Authorization
│   └── server.js  # Main server file
│
│── frontend/      # ReactJS Frontend
│   ├── src/       
│   │   ├── components/  # Reusable UI Components
│   │   ├── pages/       # Pages like Home, Login, Profile
│   │   ├── redux/       # State Management (Redux Toolkit)
│   │   ├── App.js       # Main App Component
│   │   └── index.js     # Entry Point
│
│── .gitignore
│── README.md
│── package.json


---

## 🚀 Installation & Setup  
### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/Rashi-2002/Job-Portal.git
cd Job-Portal

##Install Dependencies
sh
Copy
Edit

# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
3️⃣ Setup Environment Variables
Create a .env file in the backend directory with:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
4️⃣ Start the Development Server
sh
Copy
Edit
# Start Backend
cd backend
npm run dev

# Start Frontend
cd ../frontend
npm run dev
The app will run on http://localhost:3000 🚀
