

# Real-Time Collaborative Document Editor

This is a real-time collaborative document editor built using React.js, Node.js, and Socket.IO. It allows multiple users to write and edit shared text documents simultaneously with live synchronization across all connected clients.

---

## Technologies Used

| Frontend | Backend           | Real-Time | Database                         |
| -------- | ----------------- | --------- | -------------------------------- |
| React.js | Node.js (Express) | Socket.IO | MongoDB or PostgreSQL (optional) |

---

## Features

* Simultaneous editing with real-time synchronization
* Socket-based live communication
* Simple and modular code structure
* Easy to set up and run locally

---

## Project Structure

```
collab-editor/
├── client/         # React frontend
│   ├── src/
│   └── public/
├── server/         # Node.js backend
│   └── index.js
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/swaragharatt/collab-editor.git
cd collab-editor
```

Or manually download and extract the ZIP file.

---

### 2. Set Up the Backend

```bash
cd server
npm install
node index.js
```

The backend server will run at `http://localhost:3001`.

---

### 3. Set Up the Frontend

```bash
cd client
npm install
npm start
```

The frontend will be accessible at `http://localhost:3000`.

---

## Usage

Open the frontend in multiple browser tabs or windows. Typing in one tab will reflect instantly in others, demonstrating real-time collaboration.

---

## Output
![Screenshot 2025-06-13 033457](https://github.com/user-attachments/assets/9905577f-9d53-44bd-8b62-ff790f5f6148)

The app displays a live document editor with a shared text area. All users connected to the same session will see updates as they happen. The interface is minimal and responsive for quick testing and demonstration


---

## Potential Improvements

* Connect to a database for saving documents
* Add user authentication and session management
* Allow document creation, renaming, and deletion
* Enhance editor UI with formatting tools

---

## Author

Developed by **swaragharatt**

