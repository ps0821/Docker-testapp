# 🚀 Docker Test App

Welcome to **Docker Test App** — a simple Node.js application packaged in a Docker container to demonstrate Docker fundamentals like image building, containerization, and deployment.

## 📂 Project Overview
This repository showcases:
- Creating a Dockerfile for a Node.js app
- Building Docker images
- Running containers locally

Perfect for beginners to get hands-on experience with Docker.

---

## ⚙️ Tech Stack
- **Node.js** (Express.js)
- **Docker**

---

## 📝 Features
✅ Basic Node.js server setup  
✅ Dockerized with a lightweight image  
✅ Easy to build & run  
✅ Minimal setup, perfect for learning

---

## 🚀 Getting Started

### 1️⃣ Clone this repository
```bash
git clone https://github.com/ps0821/Docker-testapp.git
cd Docker-testapp

### 2️⃣ Build the Docker Image
```bash
docker build -t docker-testapp .
### 3️⃣ Run the Docker Container
```bash
docker run -p 3000:3000 docker-testapp
➡️ Now access the app at:
🌐 http://localhost:3000

## 🗂️ Project Structure

Docker-testapp/
├── Dockerfile         # Docker build file
├── package.json       # Node.js dependencies
├── index.js           # Main Node.js application
└── README.md          # Project documentation (this file)

##⚡ Useful Docker Commands

Action	Command
Build Docker image	docker build -t docker-testapp .
Run Docker container	docker run -p 3000:3000 docker-testapp
Stop all containers	docker stop $(docker ps -aq)
Remove all containers	docker rm $(docker ps -aq)


