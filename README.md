# User Authentication API

A clean and modular user authentication API built with Node.js, Express, MongoDB, and JWT.  
Implements registration and login functionality with encrypted passwords, authentication middleware, and controller-based architecture.  
A minimal frontend folder is included for testing and integration.

---

## Features
- User registration and login with JWT authentication  
- Password hashing using bcrypt  
- Middleware-based route protection  
- Controller-based clean code structure  
- MongoDB integration using Mongoose  
- Environment variables using dotenv  
- CORS enabled for frontend access  

---

## Tech Stack
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Mongoose ODM)  
**Authentication:** JWT, bcrypt  
**Environment Management:** dotenv  
**Frontend (Basic):** React (optional integration)  

---

## Project Structure
### Folder Overview
- **config/**
  - `db.js` → Handles MongoDB connection setup  
- **controllers/**
  - `authController.js` → Logic for registration and login  
- **middlewares/**
  - `authMiddleware.js` → JWT token verification middleware  
- **models/**
  - `User.js` → Mongoose user schema and model  
- **routes/**
  - `authRoutes.js` → Authentication routes (register, login)  
- **frontend/**
  - Placeholder for future React frontend integration  
- **index.js** → Main server entry point  
- **.gitignore** → Ignores node_modules/ and .env files  
- **package.json** → Project dependencies  

---

## Installation and Setup

## 1. Clone the Repository
git clone https://github.com/abhirambhatt/user-auth-api.git
cd user-auth-api

## 2. Install Dependencies
npm install

## 3. Run the Server
### For development:
npm run dev

## For production:
npm start

## Server will start on:
http://localhost:5000

## API Endpoints
### Register User
#### POST /api/auth/register

Request body:
{
  "username": "abhiram",
  "email": "abhi@example.com",
  "password": "123456"
}

Response:
{
  "message": "User registered successfully"
}

### Login User
#### POST /api/auth/login

Request body:
{
  "email": "abhi@example.com",
  "password": "123456"
}

Response:
{
  "message": "Login successful",
  "token": "your_jwt_token"
}

## Development Notes

- Passwords are securely hashed using bcrypt before saving.
- JWT tokens are generated for authentication and must be sent in headers for protected routes.
- Code is modularized using controllers and middlewares for scalability.

## License
This project is licensed under the MIT License.

## Author
### Abhiram Bhatt
GitHub: https://github.com/abhirambhatt

---
