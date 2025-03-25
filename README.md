Student Management System
A full-stack MERN (MongoDB, Express, React, Node.js) application for managing student records with a clean, modern user interface.
Features

Add, update, and delete student records
Responsive design
Intuitive user interface
Comprehensive student information management

Screenshots
Home Screen
![Home Screen](https://github.com/Santhosh1015/StudentManagementSystem/blob/main/sms1.png?raw=true)
Add/Edit Student Screen
![Manage Students](https://github.com/Santhosh1015/StudentManagementSystem/blob/main/sms2.png?raw=true)
Tech Stack

Frontend: React
Backend: Node.js, Express
Database: MongoDB
Styling: CSS

Prerequisites

Node.js (v14 or later)
MongoDB
npm or yarn

Installation

Clone the repository

bashCopygit clone https://github.com/yourusername/student-management-system.git
cd student-management-system

Install backend dependencies

bashCopycd backend
npm install

Install frontend dependencies

bashCopycd ../frontend
npm install
Configuration

Create a .env file in the backend directory

envCopyMONGODB_URI=your_mongodb_connection_string
PORT=4100
Running the Application

Start the backend server

bashCopycd backend
npm start

Start the frontend application

bashCopycd frontend
npm start

Project Structure
Copystudent-management-system/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── App.js
    │   ├── read.js
    │   ├── insert.js
    │   └── index.js
    └── public/
Available Scripts

npm start: Run the development server
npm build: Create a production build
npm test: Run tests

Contributions
Contributions are welcome! Please follow these steps:

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.
Contact
Your Name - santhosh1015@gmail.com
Project Link: https://github.com/Santhosh1015/student-management-system
