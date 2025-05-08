# ChatHub - Real-Time Chat App

A simple real-time chat web application built with Node.js, Express, and Socket.io. Users can join a chat room and send messages to each other instantly.

## Live Demo

👉 [Check out the live app here](https://chathub-e68o.onrender.com/)

## Features

- Real-time messaging using WebSockets (Socket.io)
- Dynamic user list updates
- Join/leave notifications
- Responsive UI with HTML, CSS, and vanilla JS
- User-friendly experience with system messages and auto-scroll

## Technologies Used

- **Node.js** & **Express** – Server-side logic
- **Socket.io** – Real-time bi-directional communication
- **HTML/CSS/JavaScript** – Frontend UI
- **Render** – Free cloud hosting

## Project Structure Overview

- `server.js` – Main server file using Express and Socket.io
- `public/` – Static assets:
  - `index.html`, `chat.html` – Frontend pages
  - `style.css` – Chat UI styling
  - `js/` – Client-side logic
- `utils/` – Modular logic for handling users and messages:
  - `users.js` – Track users joining/leaving
  - `messages.js` – Format chat messages

## 🛠️ Getting Started Locally

```bash
# Clone the repository
git clone https://github.com/tringo286/Chathub.git
cd your-repo

# Install dependencies
npm install

# Run the server
node server.js
```
