
# 🎓 LearnPath – Choose Your Learning Path

🌐 **Live Demo:**  
https://learn-path-eight.vercel.app/

📂 **GitHub Repository:**  
https://github.com/meghagaur1306-art/LearnPath


---

## 🚀 Overview

LearnPath is a full-stack interactive learning platform that allows users to explore different skill paths, track their progress, and learn step-by-step through structured checklists.  

It features an elegant interface, smooth interactivity, and real-time progress updates powered by a MERN stack backend.

Built using **MongoDB, Express.js, React.js, and Node.js**, it delivers a seamless experience with clean and responsive CSS styling.

---

## 🧩 Key Features

- ✅ User Authentication – Secure sign-up and login using JWT  
- 📚 Skill Path Selection – Choose from multiple learning categories like Frontend, Backend, etc.  
- 📊 Dynamic Progress Tracking – Updates automatically when checklist items are marked  
- 💾 Persistent Data Storage – MongoDB ensures data is retained after refresh  
- 🖥️ Interactive Dashboard – Visual representation of learning progress  
- 🧾 Custom Checklists – Manage learning items under each category  
- 📱 Responsive UI – Works smoothly across devices  
- ⚙️ MERN Stack Architecture – Scalable full-stack structure  

---

## 🛠️ Tech Stack

| Category     | Technology Used            |
|-------------|--------------------------|
| Frontend    | React.js, CSS            |
| Backend     | Node.js, Express.js      |
| Database    | MongoDB Atlas            |
| Authentication | JWT (JSON Web Token) |
| Deployment  | Vercel, Render/Railway   |
| Version Control | Git & GitHub        |

---

## 🧭 Folder Structure
MY-PROJECT/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── .env
│ ├── package.json
│ └── server.js
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── data/
│ │ ├── hooks/
│ │ ├── pages/
│ │ ├── styles/
│ │ ├── utils/
│ │ ├── App.js
│ │ └── index.js
│ ├── .env
│ └── package.json
│
└── README.md

---

## ⚙️ Environment Variables

Create `.env` files in both backend and frontend folders.

### 🔹 Backend `.env`
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### 🔹 Frontend `.env`

REACT_APP_API_URL=http://localhost:5000

---

## 🧑‍💻 Installation & Setup

Follow these steps to run the project locally on your system:

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Studentcuchd/LearnPath-Choose-Your-Learning-Path.git
cd LearnPath-Choose-Your-Learning-Path

## 🧑‍💻 Installation & Setup

Follow these steps to run the project locally on your system:

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Studentcuchd/LearnPath-Choose-Your-Learning-Path.git
cd LearnPath-Choose-Your-Learning-Path

2️⃣ Install Dependencies
🔹 Backend Setup
cd backend
npm install
🔹 Frontend Setup
cd ../frontend
npm install
3️⃣ Configure Environment Variables

Create .env files in both backend and frontend folders.

📌 Backend .env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
📌 Frontend .env
REACT_APP_API_URL=http://localhost:5000
4️⃣ Run the Application
🚀 Start Backend Server
cd backend
node server.js
👉 Backend will run at:
http://localhost:5000
🚀 Start Frontend Application
cd frontend
npm start
👉 Frontend will run at:
http://localhost:3000
