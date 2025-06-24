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

# Clone the repository
git clone https://github.com/ps0821/Docker-testapp.git
cd Docker-testapp

# Build the Docker image
docker build -t docker-testapp .

# Run the Docker container on port 3000
docker run -p 3000:3000 docker-testapp

# Your app is now accessible at:
# http://localhost:3000

# OPTIONAL Cleanup commands
# Stop all running containers
# docker stop $(docker ps -aq)

# Remove all containers (use with caution)
# docker rm $(docker ps -aq)


