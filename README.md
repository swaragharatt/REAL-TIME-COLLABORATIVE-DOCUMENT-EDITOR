
# Real-Time Collaborative Document Editor

This is a real-time document editing application built with React.js, Node.js, and Socket.IO. It allows multiple users to write and edit text simultaneously with live synchronization across all connected clients.

## Technologies Used

| Frontend | Backend | Real-Time | Database |
|----------|---------|-----------|----------|
| React.js | Node.js (Express) | Socket.IO | MongoDB or PostgreSQL (optional) |

## Features

- Live collaborative text editing
- Real-time communication between clients
- Simple modular structure
- Easy to run locally for testing or development

## Project Structure

collab-editor/
├── client/         # React frontend
│   ├── src/
│   └── public/
├── server/         # Node.js + Express backend
│   └── index.js
└── README.md


## Getting Started

### 1. Clone or Download the Repository

bash
git clone https://github.com/swaragharatt/collab-editor.git
cd collab-editor

Or download the ZIP and extract it manually.

### 2. Set Up the Backend

Navigate to the server directory, install dependencies, and start the server:

bash
cd server
npm install
node index.js

The backend server will start at `http://localhost:3001`.

### 3. Set Up the Frontend

Navigate to the client directory, install dependencies, and start the development server:

bash
cd client
npm install


The frontend will open in the browser at `http://localhost:3000`.

## Usage
To test collaborative functionality, open `http://localhost:3000` in multiple browser windows or tabs. Typing in one window will reflect in real time in all others.

## Potential Improvements
* Integration with a database to save documents
* User authentication system
* Document management (create, rename, delete)
* Editor enhancements and styling improvements

## Author
Developed by [swaragharatt]

`
