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

2️⃣ Build the Docker Image
docker build -t docker-testapp .
3️⃣ Run the Docker Container
docker run -p 3000:3000 docker-testapp
➡️ Now access the app at:
🌐 http://localhost:3000

🗂️ Project Structure

Docker-testapp/
├── Dockerfile         # Docker build file
├── package.json       # Node.js dependencies
├── index.js           # Main Node.js application
└── README.md          # Project documentation (this file)
⚡ Useful Docker Commands

Action	Command
Build Docker image	docker build -t docker-testapp .
Run Docker container	docker run -p 3000:3000 docker-testapp
Stop all containers	docker stop $(docker ps -aq)
Remove all containers	docker rm $(docker ps -aq)
👨‍💻 Author

Palak Seth
🔗 LinkedIn (Add your profile URL here)

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

📄 License

This project is licensed under the MIT License.


---

**Optional Add-ons (on request):**
- Shields/badges (e.g., `Build Passing`, `Docker`, `Node.js`)
- Contribution guidelines template
- DockerHub publishing README section

Just say the word if you need those. ✅
