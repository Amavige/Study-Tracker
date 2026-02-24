📚 Study Tracker

A full-stack web application that helps users track study sessions, monitor progress, and stay consistent with learning goals.

This project demonstrates secure authentication, RESTful API design, full CRUD functionality, and data tracking with protected routes.

🚀 Features
🔐 Authentication

User registration

Secure login

Password hashing with bcrypt

JWT-based authentication

Protected routes

📊 Study Tracking

Create subjects

Log study sessions

Edit and delete sessions

Track total hours per subject

View weekly/monthly progress

📈 Analytics (Planned / In Progress)

Study streak tracking

Goal completion percentage

Most studied subject

Data visualization charts

🛠 Tech Stack

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT (JSON Web Token)

bcrypt

Frontend (Planned / Optional)

React

Tailwind CSS

📂 Project Structure
study-tracker/
│
├── server.js
├── package.json
├── .env
│
├── models/
├── routes/
├── controllers/
├── middleware/

🔑 Authentication Flow

User registers with email and password

Password is hashed before saving to database

User logs in

Server returns JWT token

Protected routes require valid token

🧪 API Endpoints (Current)
Auth Routes

POST /api/auth/register
POST /api/auth/login

Protected Route Example

GET /api/dashboard

⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/study-tracker.git
cd study-tracker

Install dependencies:

npm install

Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run the server:

npx nodemon server.js
🎯 Project Goals

This project is being built to:

Practice backend architecture

Implement secure authentication

Design scalable API structure

Demonstrate full CRUD functionality

Strengthen full-stack development skills

📌 Future Improvements

Frontend dashboard

Data visualization charts

Pomodoro timer integration

Goal reminders

Deployment (Render / Railway / Vercel)

👨‍💻 Author

Amiel Thompson
Full-Stack Developer (in progress 🚀)
