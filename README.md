# Chat Application with Real-Time Messaging

## Overview

This is a real-time chat application built using Node.js and Socket.IO. The application facilitates seamless communication between users with features such as real-time messaging, user notifications, and a user-friendly interface. 

## Features

- Real-time messaging between users
- User join and leave notifications
- Basic chat UI with message display
- Media sharing capabilities (planned for future development)

## Technologies Used

- **Node.js**: Server-side JavaScript runtime environment
- **Socket.IO**: Real-time communication library for web applications
- **Express.js**: Web framework for Node.js
- **HTML/CSS/JavaScript**: Frontend development
- **Nodemon**: Development tool for auto-reloading the server

## Live Demo

You can view the live version of the application at the following link:

- [Live Demo](https://chitchat-realtime-nodesocket-vats.netlify.app)

## Getting Started

To get a local copy of this project up and running, follow these instructions:

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vats-sanskriti/ChitChat.git
Navigate to the project directory:

bash
Copy code
cd chat-app
Install dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
Alternatively, if you’re using Nodemon:

bash
Copy code
npm run dev
The server will start and listen on port 8000.

Open the application in your browser:

Go to http://localhost:8000 to see the chat application in action.

Usage
Joining the Chat: Upon opening the application, you will be prompted to enter your name to join the chat.
Sending Messages: Type your message into the input field and press Enter or click the Send button to send a message.
Media Sharing: (Planned Feature) Users will be able to share images and other media files in future updates.
Challenges and Solutions
CORS Policy Issue: Initially faced challenges with CORS policy, which were resolved by configuring the server to handle cross-origin requests appropriately.
Message Synchronization: Implemented real-time messaging effectively despite initial synchronization challenges.
Future Improvements
Implement media sharing capabilities (images, videos, etc.)
Add user authentication and authorization
Optimize performance for scalability
Enhance UI/UX with additional features and improvements
