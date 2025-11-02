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
- **.env** → Environment variables  
- **package.json** → Project dependencies  

---

## Environment Variables
Create a `.env` file in the root directory:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

---

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/YOURUSERNAME/user-auth-api.git
cd user-auth-api


