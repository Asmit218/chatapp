Chat Application
A full-stack, real-time chat application built with the MERN stack and Socket.IO. This project features user authentication (login/register) and seamless instant messaging.

🌐 Live Demo
You can try out the live application here:
https://chatapp-sandy-tau.vercel.app/

✨ Features
User Authentication: Secure login and registration functionality.

Real-Time Messaging: Instant, bidirectional communication between users using Socket.IO.

MongoDB Integration: Data persistence for user information.

RESTful API: A robust backend to handle user requests.

💻 Technologies Used
This application is built with a modern stack of technologies.

Frontend:

Vite-React

Tailwind CSS

Backend:

Node.js

Express.js

MongoDB

Real-Time Communication:

Socket.IO

Deployment:

Frontend: Vercel

Backend: Render

🚀 Installation and Local Setup
To get a copy of this project up and running on your local machine, follow these simple steps.

Prerequisites
Node.js (v18 or higher)

npm

A MongoDB database (local or cloud-based)

Backend (Server) Setup
Navigate to the server directory.

```Bash

cd server
Install the required Node.js packages.
```
```Bash

npm install
Create a .env file in the server directory and add your MongoDB connection string and other environment variables.

PORT=5000
MONGODB_URI=<Your MongoDB Connection String>
FRONTEND_URL=http://localhost:5173  # Or your frontend dev URL
Start the backend server.
```
```Bash

npm run start
Frontend (Client) Setup
Open a new terminal and navigate to the client directory.
```
```Bash

cd client
Install the required npm packages.
```
```Bash

npm install
Start the frontend development server.
```
```Bash

npm run dev
The application should now be running on http://localhost:5173 and connected to your local backend.
```
