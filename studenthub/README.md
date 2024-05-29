Webstack - Portfolio Project

Project Structure

studenthub/
├── controllers/
│   ├── authController.js
│   └── studentController.js
├── models/
│   ├── user.js
│   └── student.js
├── routes/
│   ├── authRoutes.js
│   └── studentRoutes.js
├── middleware/
│   └── authMiddleware.js
├── config/
│   └── db.js
├── .env
├── app.js
└── package.json

Setup

mkdir studenthub
cd studenthub
npm init -y
npm install express mongoose bcryptjs jsonwebtoken dotenv

Running the Project

node app.js

API Endpoints:User Registration: POST /api/auth/registerUser Login: POST /api/auth/loginCreate Student: POST /api/studentsGet All Students: GET /api/studentsGet Student by ID: GET /api/students/:idUpdate Student: PUT /api/students/:idDelete Student: DELETE /api/students/:id


