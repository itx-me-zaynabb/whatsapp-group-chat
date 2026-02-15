💬 WhatsApp Group Chat – Real-Time Chat App

A real-time group chat application built using NestJS and WebSockets that allows multiple users to communicate instantly in a shared chat room.

This project demonstrates backend real-time communication using WebSocket architecture and socket-based message broadcasting.

🚀 Features

🔴 Real-time messaging using WebSockets

👥 Group chat functionality

📡 Instant message broadcasting

🔄 Live user updates

🧠 Clean modular architecture (NestJS structure)

🌐 Simple frontend using index.html

⚡ Event-driven socket communication

🛠️ Tech Stack
Backend

NestJS

WebSocket (Socket.io)

Node.js

TypeScript

Frontend

HTML

CSS

JavaScript

Socket.io Client

📂 Project Structure
src/
 ├── app.module.ts
 ├── main.ts
 ├── chat/
 │     ├── chat.gateway.ts
 │     ├── chat.module.ts
 │     └── chat.service.ts

public/
 └── index.html

⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/itx-me-zaynabb/whatsapp-group-chat.git
cd whatsapp-group-chat

2️⃣ Install Dependencies
npm install

3️⃣ Run the Server
npm run start


Server will start at:

http://localhost:3000

🧩 How It Works

NestJS WebSocket Gateway handles socket connections.

When a user sends a message, it is emitted to the server.

The server broadcasts the message to all connected clients.

Clients update UI instantly without page refresh.

📌 Key Concepts Used

WebSocket Gateway

Real-time event handling

Socket broadcasting

Modular backend architecture

Client-server communication model

🧠 Challenges Faced During Development

WebSocket connection errors

CORS configuration issues

Handling multiple client connections

Real-time message synchronization

Git remote & deployment errors

🎯 Future Improvements

Private messaging

User authentication

Message timestamps

Online/offline status

Database integration (MongoDB / PostgreSQL)

Typing indicators

File sharing

📸 Demo

Run locally and open multiple browser tabs to simulate multiple users.

👩‍💻 Author

Zainab Fatima
Frontend Developer | React & JavaScript
