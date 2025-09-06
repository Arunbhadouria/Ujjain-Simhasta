 🕉️ Ujjain Simhasta – Smart Pilgrimage Management System

## 📖 Overview
**Ujjain Simhasta** is a smart pilgrimage management platform designed to assist millions of devotees during **Simhastha 2028** in Ujjain.  
It provides real-time assistance, navigation, and essential services such as **live darshan, ticket booking, lost & found, smart parking, and emergency support**.  

This project is built to enhance **mobility, accessibility, and management** for both pilgrims and authorities.  

---

## ✨ Features
- 📍 **Interactive Maps** – Navigate Mandirs, Ghats & Parking zones.  
- 🎥 **Live Darshan** – Watch live darshan streams of temples.  
- 🎟️ **Ticket Booking System** – Book & reschedule darshan tickets with QR verification.  
- 📢 **Notice Board** – Real-time updates & announcements.  
- 🧳 **Lost & Found** – Report & recover lost items digitally.  
- 🚗 **Smart Parking** – Locate and reserve nearby parking spots.  
- 🚨 **Emergency Assistance** – Quick help during emergencies.  
- ♿ **Divyangjan Access** – Special focus on accessibility for differently-abled & elderly.  

---

## 🛠️ Tech Stack
### **Frontend**
- React.js + TailwindCSS  
- Leaflet.js (Maps)  
- Axios (API Calls)  

### **Backend**
- Node.js + Express.js  
- Sequelize ORM + PostgreSQL/MySQL  
- JWT Authentication  
- Nodemailer (Email Notifications)  

### **Other Tools**
- Helmet.js (Security)  
- CORS Configuration  
- Vercel (Frontend Hosting)  
- Render/Heroku/AWS (Backend Hosting)  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Arunbhadouria/Ujjain-Simhasta.git
cd Ujjain-Simhasta
2️⃣ Backend Setup
bash
Copy code
cd Backend
npm install
Create a .env file in Backend/ and add:

env
Copy code
PORT=3001
DB_HOST=localhost
DB_USER=your_username
DB_PASS=your_password
DB_NAME=ujjain_simhasta
JWT_SECRET=your_secret_key
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
Start backend server:

bash
Copy code
npm run dev
3️⃣ Frontend Setup
bash
Copy code
cd ../Frontend
npm install
npm start
4️⃣ Access the App
Frontend: http://localhost:3000

Backend API: http://localhost:3001

📂 Project Structure
csharp
Copy code
Ujjain-Simhasta/
│── Backend/        # Express.js backend
│   ├── config/     # Database config
│   ├── routes/     # API routes
│   ├── models/     # Sequelize models
│   ├── middlewares/# Error handling, auth
│   └── uploads/    # Uploaded files (lost & found, tickets)
│
│── Frontend/       # React.js frontend
│   ├── src/        # Components & pages
│   ├── public/     # Static files
│
│── README.md       # Project documentation
🤝 Contribution
Contributions are welcome!

Fork the repo

Create a new branch (feature/xyz)

Commit changes

Push to your fork and submit a PR

📜 License
This project is licensed under the MIT License – feel free to use and modify with attribution.

👥 Team
Arun Bhadouria – Project Owner

Harsh Manmode – Backend & API Development

Contributors – See commits

🌐 Deployment Links
🔗 Frontend: Ujjain-Simhasta (Vercel)

🔗 Backend API: API Endpoint
