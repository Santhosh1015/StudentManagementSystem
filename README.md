# Student Management System

A full-stack MERN (MongoDB, Express, React, Node.js) application for managing student records with a clean, modern user interface.

## Features
- Add, update, and delete student records
- Responsive design
- Intuitive user interface
- Comprehensive student information management

## Screenshots
Home Screen  
![Home Screen](https://github.com/Santhosh1015/StudentManagementSystem/blob/main/sms1.png?raw=true)  
Add/Edit Student Screen  
![Manage Students](https://github.com/Santhosh1015/StudentManagementSystem/blob/main/sms2.png?raw=true)  

## Tech Stack
- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Styling:** CSS

## Prerequisites
- Node.js (v14 or later)
- MongoDB
- npm or yarn

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Santhosh1015/StudentManagementSystem.git
cd student-management-system
```
2. Install backend dependencies:
```bash
cd backend
npm install
```
3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

## Configuration
Create a `.env` file in the `backend` directory:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=4100
```

## Running the Application
1. Start the backend server:
```bash
cd backend
npm start
```
2. Start the frontend application:
```bash
cd ../frontend
npm start
```

## Project Structure
```
student-management-system/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── App.js
    │   ├── read.js
    │   ├── insert.js
    │   └── index.js
    └── public/
```

## Available Scripts
- `npm start`: Run the development server
- `npm build`: Create a production build
- `npm test`: Run tests

## Contributions
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:
```bash
git commit -m 'Add some AmazingFeature'
```
4. Push to the branch:
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Santhosh - santhosh1015@gmail.com  
Project Link: [GitHub Repository](https://github.com/Santhosh1015/StudentManagementSystem)

