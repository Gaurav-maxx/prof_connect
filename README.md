🚀 ProfConnect – Professor Appointment Booking System

ProfConnect is a full-stack MERN application developed for students of National Institute of Technology Kurukshetra that enables seamless interaction between students and professors through appointment scheduling, real-time communication, and centralized administration.

The platform allows students to book appointments with professors department-wise, professors to manage availability and publish academic updates, and admins to monitor and manage the complete system.
https://profconnect-1.onrender.com/
🚀 Live Demo


✨ Features
👨‍🎓 Student Module
Student Registration & Login
Browse Professors by Department
Book Appointments
Manage Personal Profile
View Appointment History
Access Real-Time Posts & Announcements
👨‍🏫 Professor Module
Professor Dashboard
Manage Availability
Update Profile Information
View Student Appointments
Publish Real-Time Academic Posts
Share Notices, Resources & Updates
🛠️ Admin Module
Add / Manage Professors
Monitor Appointments
Manage Departments & Users
Centralized Admin Dashboard
System Monitoring & Control
⚡ Real-Time Features

Implemented using Socket.IO:

Live professor announcements
Instant post updates
Real-time notification broadcasting
Dynamic academic feed without page refresh
🏫 Departments Supported
Computer Science Engineering
Electronics & Communication Engineering
Electrical Engineering
Mechanical Engineering
Civil Engineering
Production & Industrial Engineering (PIE)
🧰 Tech Stack
Frontend
React.js
Tailwind CSS
React Router DOM
Axios
React Toastify
Backend
Node.js
Express.js
MongoDB
JWT Authentication
Socket.IO
📂 Project Structure
client/
│
├── src/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── assets/
│   └── App.jsx
│
server/
│
├── controllers/
├── middleware/
├── models/
├── routes/
├── config/
└── server.js
🔐 Authentication
JWT-based Authentication
Role-Based Access Control
Protected Routes for:
Students
Professors
Admins
📸 Major Functionalities
Appointment Booking

Students can:

View professor profiles
Check availability
Book appointments directly
Professor Dashboard

Professors can:

Update profile details
Manage availability
View booked appointments
Create real-time posts
Admin Panel

Admins can:

Manage professors
Monitor users & appointments
Control platform operations
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone <your-repository-link>
cd profconnect
2️⃣ Install Dependencies
Frontend
cd client
npm install
Backend
cd server
npm install
🔑 Environment Variables

Create a .env file inside the server folder:

MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=4000
▶️ Run Application
Start Backend
cd server
npm run server
Start Frontend
cd client
npm run dev
🌟 Project Highlights
MERN Stack Architecture
Real-Time Communication with Socket.IO
Role-Based Access Control
Dynamic Routing & Filtering
Responsive UI Design
RESTful API Integration
Reusable Component Architecture
📌 Future Improvements
Video Meeting Integration
Email Notifications
Chat System
AI-Based Appointment Suggestions
Timetable Synchronization
👨‍💻 Developer

Avnish Singh
B.Tech ECE Student
National Institute of Technology Kurukshetra

📄 License

This project is developed for educational and academic purposes.
