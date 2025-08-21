# 💬 Real-Time Chat Application

A simple **real-time chat application** built with **Node.js**, **Express**, and **Socket.IO**.  
Users can join chat rooms, send messages, and share their live location in real-time.

---

## 🚀 Features
- Join with a **username** and **room**
- Real-time messaging using **WebSockets**
- Broadcast when a user **joins** or **leaves** a room
- Share **current location** (Google Maps link)
- Profanity filter using **bad-words**
- Dynamic sidebar showing **room info** and **active users**

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express, Socket.IO  
- **Frontend:** HTML, CSS, Vanilla JS, Mustache.js, Moment.js  
- **Deployment:** Render

---

## 📂 Project Structure
chat_app/
│
├── public/ # Static frontend files (HTML, CSS, JS)
│ ├── js/
│ │ └── chat.js # Client-side socket logic
│ ├── css/
│ │ └── index.css # Styles
│ └── index.html
│
├── src/
│ ├── utils/
│ │ ├── messages.js # Message formatting helpers
│ │ └── users.js # User management (add/remove/get)
│ └── index.js # Server entry point
│
├── package.json
└── README.md
