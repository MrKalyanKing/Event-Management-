# 🤝 Contributing to Event Management System

Thank you for your interest in contributing to the **Event Management System** 🎉  
This document explains **how to set up the project locally**, **how to work on issues**, and **how to follow our Git workflow correctly**.

Please read this fully before contributing.

---

## 📌 Project Overview

A full-stack **Event Management System** built with a modern frontend and backend architecture.  
The project is designed for **scalable development**, **multiple contributors**, and **high code quality**.

We strictly follow:
- Structured Git workflow
- Docker-based development
- CI-enforced quality checks
- Issue & Pull Request templates

---

## 🧱 Tech Stack

### Frontend
- ⚛️ React
- ⚡ Vite
- 🟢 Node.js

### Backend
- 🟢 Node.js
- 🚂 Express
- 🍃 MongoDB

### Dev & Ops
- 🐳 Docker & Docker Compose
- 🤖 GitHub Actions (CI)
- 🧩 GitHub Issues & PR Templates

---

## 🌿 Branch Strategy

| Branch       | Purpose                |
|-------------|------------------------|
| `main`      | Production-ready code  |
| `develop`   | Active development     |
| `feature/*` | New features           |
| `fix/*`     | Bug fixes              |

⚠️ **Direct pushes to `main` and `develop` are blocked**  
All changes must go through **Pull Requests**.

---

## 🚀 Local Development Setup

You can run this project **with Docker (recommended)** or **without Docker**.

---

## ✅ Option 1: Run with Docker (Recommended)

Docker ensures everyone runs the **same environment**.

### 🔧 Prerequisites
- Docker
- Docker Compose

Verify installation:
```bash
docker --version
docker compose version
```



## ▶️ Server setup
``` bash
 docker compose up --build
```

## 🌐 Services

- Frontend → http://localhost:5173
- Backend → http://localhost:8080
- MongoDB → localhost:27017

## ⏹ Stop the application
```1 bash
docker compose down
```

## ✅ Option 2: Run without Docker

Use this only if Docker is unavailable.

## 🔧 Prerequisites

- Node.js (v18 or above)
- MongoDB running locally

## ▶️ Backend Setup
- cd backend
- npm install
- npm run dev

Backend runs at:
http://localhost:8080

## ▶️ Frontend Setup
- cd frontend
- npm install
- npm run dev

Frontend runs at:
http://localhost:5173

