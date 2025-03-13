# MERN Stack Chat Application

## Overview
This is a real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack with Socket.io for real-time messaging. The application allows users to communicate instantly and includes features like chat history, an admin dashboard, and user authentication.

## Features
- Real-time messaging using **Socket.io**
- User authentication (Signup/Login)
- Chat history display
- Admin dashboard for monitoring chats
- Responsive UI using **Tailwind CSS**
- Deployed frontend on **Vercel** and backend on **Render**

## Tech Stack
- **Frontend**: React, Tailwind CSS, HTML, JavaScript
- **Backend**: Node.js, Express.js, MongoDB
- **Real-time Communication**: Socket.io
- **Database**: MongoDB
- **Deployment**: Vercel (Frontend), Render (Backend)

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- Node.js
- MongoDB
- Git

### Steps to Run Locally
#### Clone the repository
```sh
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

#### Backend Setup
```sh
cd backend
npm install
```
Create a **.env** file in the `backend` directory and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```
Start the backend server:
```sh
npm start
```

#### Frontend Setup
```sh
cd ../frontend
npm install
```
Start the React application:
```sh
npm start
```

## Usage
1. Open `http://localhost:3000/` in your browser.
2. Register/Login to access the chat.
3. Start a conversation with other users in real-time.
4. Admin can monitor chat messages from the dashboard.

## Deployment
### Deploy Frontend on Vercel
```sh
vercel
```

### Deploy Backend on Render
1. Push your backend code to GitHub.
2. Create a new Web Service on Render and connect your GitHub repo.
3. Set the environment variables as in `.env`.
4. Deploy and get the backend URL.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss the change.





- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
