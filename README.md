# Auth & Profile API - Node.js & Express

This is a simple authentication and profile management API built using Node.js, Express, and MongoDB. It supports user registration, login, profile retrieval, profile update, logout, and access token refresh using JWT.

## Features

- User Signup with profile image upload  
- User Login (with JWT access & refresh tokens)  
- Get Logged-in User Profile  
- Update User Profile (including profile image)  
- Refresh Access Token using Refresh Token  
- Secure Logout with refresh token clearing  

## Tech Stack

- Backend: Node.js, Express.js  
- Database: MongoDB 
- Authentication: JWT (Access + Refresh Tokens)  
- File Uploads: Multer  
- Validation: express-validator  
- Other Tools: Postman, Git, VS Code  

## Folder Structure

.  
├── config/  
│   └── db.js, multer.js  
├── controllers/  
│   └── auth.Controller.js, profile.Controller.js  
├── middlewares/  
│   └── authMiddleware.js  
├── models/  
│   └── User.js  
├── routes/  
│   └── auth.Routes.js, profile.Routes.js  
├── uploads/  
│   └── profiles/  
├── .env  
├── server.js  
└── README.md  


## Create a .env file and add the following:

PORT=3000  
MONGO_URI=your_mongodb_connection  
JWT_SECRET_ACCESS=your_access_secret  
JWT_SECRET_REFRESH=your_refresh_secret



## Installation & Setup & install

```bash
git clone https://github.com/Hasnaa-Nageh/auth-profile-api-nodejs.git  
cd auth-profile-api-nodejs  
npm install
npm run dev
