# MERN Full Stack Project

This project is a full-stack web application built using the **MERN stack**:
- **MongoDB** - Database
- **Express.js** - Backend Framework
- **React.js (Vite)** - Frontend UI
- **Node.js** - Server Runtime

The project is divided into two main folders:

MY PROJECT/
│
├── home/ # Frontend (React + Vite + Tailwind CSS)
│ ├── src/
│ ├── public/
│ ├── index.html
│ └── package.json
│
└── server/ # Backend (Node.js + Express + MongoDB)
├── index.js / server.js (your main backend file)
├── routes/
├── models/
└── package.json

yaml
Copy code

---

## 🚀 Features
- Fully responsive UI built using **React.js & Tailwind CSS**
- REST APIs using **Node.js & Express.js**
- **MongoDB** as the database (local or cloud - MongoDB Atlas)
- Modular folder structure

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone <your-repo-link>
cd "MY PROJECT"
2️⃣ Install Frontend Dependencies
bash
Copy code
cd home
npm install
To start the frontend:

bash
Copy code
npm run dev
The frontend will run on:
http://localhost:5173

3️⃣ Install Backend Dependencies
bash
Copy code
cd ../server
npm install
Before running the backend, create a .env file inside /server:

ini
Copy code
MONGO_URI=your_mongodb_connection_uri
PORT=5000
Start the backend:

bash
Copy code
npm start
The backend will run on:
http://localhost:5000

🔗 Connecting Frontend & Backend
In your frontend API calls, use:

js
Copy code
http://localhost:5000/api/...
If needed, create a .env file inside /home:

ini
Copy code
VITE_API_URL=http://localhost:5000
🧪 Recommended Tools
Tool	Purpose
VS Code	Code Editing
Postman / Thunder Client	Testing APIs
MongoDB Compass	Viewing Database
Git & GitHub	Version Control

✅ Running Full Project
Open two terminals:

Terminal 1: Frontend

bash
Copy code
cd home
npm run dev
Terminal 2: Backend

bash
Copy code
cd server
npm start
👨‍💻 Author
Venu Gopal
MERN Full Stack Developer


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
