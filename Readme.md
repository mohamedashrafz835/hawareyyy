# 🐳 MyApp - Dockerized Application

This repository contains a simple application packaged with Docker and automatically built & pushed to **Docker Hub** using GitHub Actions.

---

## 🚀 Run the App with Docker

### 1. Pull the image from Docker Hub
```bash
docker pull 835835/myapp:latest
```

### 2. Run the container
```bash
docker run -d -p 8000:8000 835835/myapp:latest
```

### 3. Access the app
Open your browser and go to:  
👉 [http://localhost:8000](http://localhost:8000)

---