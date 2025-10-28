# 🚀 CollabMind – Collaborative AI-Powered Project Platform

## 💡 Overview  
**CollabMind** is a full-stack **AI-powered project collaboration platform** that combines the best of **Trello**, **Notion**, **Slack**, and **Miro** into one unified workspace.  
It enables seamless teamwork with real-time collaboration tools, intelligent ideation assistance, and dynamic project management — all in one place.

This project was developed as part of my **Full Stack Development Internship at Infotact Solutions**, where I focused on integrating **real-time communication**, **AI-powered idea generation**, and **scalable task management**.

---

## 📁 Folder Structure  
The project is divided into two main directories:

- `frontend/` → Built with **React**, **Tailwind CSS**, and **Vite**.  
- `backend/` → Developed using **Node.js**, **Express.js**, and **MongoDB**.

---

## ⚙️ Key Features  

- 🔐 **User Authentication & Role-Based Access Control (RBAC):** Admin, Manager, and Member roles.  
- 🤖 **AI Assistant:** Helps generate ideas, brainstorm solutions, and summarize discussions using **Gemini API**.  
- 📋 **Kanban-Style Task Management:** Drag-and-drop interface for organizing tasks by project stages.  
- 🖊 **Real-Time Whiteboard:** Create shapes, lines, and mind maps; clear boards collaboratively.  
- 💬 **Project-Based Group Chat:** Real-time threaded discussions and instant notifications with **Socket.IO**.  
- 🗂 **Project & Task APIs:** Full **CRUD operations** implemented using **Express** and **MongoDB**.  
- 📊 **Analytics Dashboard:** Visual insights for project progress, team performance, and deadlines.  
- ⚙️ **Admin Panel:** Manage users, roles, and projects efficiently from a unified dashboard.

---

## 🛠️ Tech Stack  

| Category | Technologies |
|-----------|--------------|
| **Frontend** | React.js ⚛️ · Vite ⚡ · Tailwind CSS 💠 |
| **Backend** | Node.js 🟩 · Express.js 🚀 |
| **Database** | MongoDB 🍃 |
| **Real-Time** | Socket.IO ⚡ |
| **Authentication** | JWT 🔑 |
| **AI Integration** | Gemini API 🤖 |
| **Other Tools** | Git 🧠 · GitHub 🐙 · Postman 📬 · VS Code 💻 |

---

## 📈 Installation & Setup  

Follow these steps to run **CollabMind** locally:

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/collabhub.git

# 2. Navigate to the project folder
cd collabhub

# 3. Install dependencies for both frontend and backend
cd frontend && npm install
cd ../backend && npm install

# 4. Start the backend server
npm run server

# 5. Start the frontend
npm run dev
