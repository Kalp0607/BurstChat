# BurstChat 💬

BurstChat is a real-time chat application built using the MERN stack.
It allows users to sign up, log in, and send real-time messages with image sharing.

## 🚀 Features

- User Authentication (Signup/Login)
- Real-time Messaging using Socket.io
- Image Uploads using Cloudinary
- Online User Status
- Modern UI with React + Tailwind
- Secure password hashing using bcrypt

## 🛠 Tech Stack

Frontend:

- React
- Tailwind CSS
- Zustand
- Axios

Backend:

- Node.js
- Express.js
- MongoDB
- Socket.io
- Cloudinary

## 📁 Project Structure

```
BurstChat
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── middleware
│
├── frontend
│   ├── components
│   ├── pages
│   ├── store
│   └── lib
│
└── package.json
```

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/Kalp0607/BurstChat.git
```

### 2. Install dependencies

Backend

```
cd backend
npm install
```

Frontend

```
cd frontend
npm install
```

### 3. Setup Environment Variables

Create `.env` file inside backend:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx
```

### 4. Run the project

Backend

```
npm run dev
```

Frontend

```
npm run dev
```

## 👨‍💻 Author

Kalp Shah
