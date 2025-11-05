# 🎓 College Feedback Portal

A full-stack web application for collecting and analyzing student feedback on classroom and event experiences. Built with Node.js, Express, SQLite, and vanilla HTML/CSS/JS.

## 🔧 Features
- 👥 Role-based login (Student / Staff)
- 📝 Dynamic feedback form (Classroom / Event)
- 🌐 Tamil/English toggle
- 🧠 Sentiment detection
- 🔔 Staff email notification
- 📊 Staff dashboard with feedback summary
- 📥 CSV download from database

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js + Express
- Database: SQLite
- Email: Nodemailer

## 🚀 Setup Instructions
1. Clone repo and open in VS Code
2. Run `npm install`
3. Create `.env` file with:
STAFF_EMAIL=yourstaffemail@gmail.com STAFF_PASS=yourpassword STAFF_PASSWORD=admin123
4. Run server:
node backend/server.js
5. Open `frontend/login.html` in browser

## 📁 Folder Structure
See `college-feedback-portal/` for full modular breakdown.