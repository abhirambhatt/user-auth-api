# User Authentication API

A secure and scalable User Authentication & Management API built with Node.js, Express, MongoDB, and JWT Authentication.  
Includes user registration, login, password hashing with bcrypt, and file uploads using Firebase Storage.

---

## Features
- User registration and login with JWT authentication
- Password encryption using bcrypt
- Middleware for authentication and error handling
- File upload with Firebase Storage
- CRUD APIs following REST architecture
- Mongoose models for database management
- Tested using Postman or Thunder Client

---

## Tech Stack
**Backend:** Node.js, Express.js  
**Database:** MongoDB, Mongoose  
**Authentication:** JWT, bcrypt  
**File Storage:** Firebase Storage  
**API Testing:** Postman / Thunder Client  
**Version Control:** Git and GitHub  

---

## Project Structure
user-auth-api/
├── models/
│ └── User.js
├── routes/
│ └── authRoutes.js
├── middleware/
│ └── authMiddleware.js
├── config/
│ └── firebase.js
├── index.js
├── package.json
└── README.md


---

## Installation and Setup

### 1. Clone the repository
```bash
git clone https://github.com/abhirambhatt/user-auth-api.git
cd user-auth-api
