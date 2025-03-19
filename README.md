# Real Time Chat App

A real-time web based chat applciation like whatsapp web.

## Live Links :

https://city-street-shops.vercel.app

https://chat-app-g430.onrender.com (Cold start)
  
## Features

<li>Live chat feature using socket.io</li>
<li>JWT based user authentication</li>
<li>Group chat and one-to-one chat features</li>
<li>Cloud storage of images</li>
<li>Live new chat message notification feature</li>
<li>Feature to indicate when the other user is typing</li>

## Tech Stack

- **Node.js** (Backend)
- **Express.js** (API Framework)
- **Mongoose** (ORM for MongoDB)
- **MongoDB Atlas** (Cloud Database)
- **Cloudinary** (Images storage on cloud)
- **Multer** (Middleware for file uploads)
- **Socket IO** (Live chat)
- **Vercel and Render** (Deployment)
- **JWT** (User authentication/authorization)

## Steps to run in local environment

### Prerequisites

- **Node.js** v20+

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/Deepak-Dalal/City-Street-Shops.git
   ```
2. Navigate to backend directory:
   ```
   cd backend
   ```
3. Set up backend environment variables:
   - Create a `.env` file in the backend directory.
   - Add the following:
     ```env
     MONGO_URI=your_mongodb-atlas-url
     ```
4. Install backend dependencies
   ```
   npm install
   ```
5. Start backend server
   ```
   npm start
   ```
6. Navigate to frontend directory:
   ```
   cd frontend
   ```
7. Set up frontend environment variables:
   - Create a `.env` file in the frontend directory.
   - Add the following:
     ```env
     VITE_REACT_APP_BACKEND_BASE_URL='http://localhost:5000'
     ```
8. Install frontend dependencies
   ```
   npm install --legacy-peer-deps
   ```
9. Start frontend server
   ```
   npm run dev
   ```

The API will be accessible at `http://localhost:3000`.

## Screens

### Login screen
![image](https://github.com/Deepak-worthy/chat-app/assets/82026071/46bde34a-e5aa-47ba-96d3-12f2f90ded3b)

### Sign-up screen
![image](https://github.com/Deepak-worthy/chat-app/assets/82026071/7f19d481-4c7b-4128-a404-9a91656ae241)

### Chat screen
![image](https://github.com/Deepak-worthy/chat-app/assets/82026071/3b0455cb-4ed5-4878-a7bd-491dc88ad4b8)

### Group chat profile
![image](https://github.com/Deepak-worthy/chat-app/assets/82026071/8c303da3-9ca4-4bd1-ad8e-c895ece434ce)

### Individual user profile
![image](https://github.com/Deepak-worthy/chat-app/assets/82026071/c9883e7f-9c76-4539-b83e-964fae3caac6)
