# 🚀 FlaskApp DevOps Project

*Simplifying microservice deployment with CI/CD automation and containerization.*

![Last Commit](https://img.shields.io/badge/last%20update-today-success)
![Python](https://img.shields.io/badge/codebase-85.4%25%20Python-blue)
![Languages](https://img.shields.io/badge/languages-2-informational)

---

## 📘 Project Summary

**FlaskApp DevOps Project** is crafted to streamline the end-to-end workflow of a microservice using **Flask**, **Docker**, and **Jenkins**. It supports automated deployment, health monitoring, and testing pipelines — all tailored for scalable environments.


---

## 🌟 Highlights

- 📦 **Dockerized Deployments**: Seamless portability and environment consistency  
- 🔁 **CI/CD Integration**: Jenkins-powered automation  
- 📍 **Health Check Endpoints**: Built-in diagnostics (`/health`, `/metrics`, `/logs`)  
- 🔧 **Unified Configuration**: Simplified config management  
- 📑 **Central Logging**: View logs in one place  

---

## ⚙️ Setup Guide

### ✅ Requirements

Ensure the following are installed:

- Python (v3 or later)  
- pip (Python package manager)  
- Docker (for containerization)  
- Jenkins (recommended for CI/CD workflows)  

---

## 🧱 Clone & Build

### Clone the Repository

```bash
git clone https://github.com/TejPATHAK/Project-Devops-Flaskapp.git
```

### Build Docker Image

```bash
docker build -t flaskapp-devops .
```

---

## 🧪 Local Run

### Run without Docker

```bash
pip install -r requirements.txt
python app.py
```

---

## 🧰 App Features

### Run with Docker

```bash
docker run -p 5000:5000 flaskapp-devops
```

### Available Endpoints

| Route       | Description              |
|-------------|--------------------------|
| `/`         | Base route (Hello World) |
| `/health`   | Health check             |
| `/metrics`  | Performance metrics      |
| `/logs`     | Application logs         |

---

## 🧪 Testing

### Run tests locally

```bash
pytest test_app.py
```

### Run tests inside Docker (if supported):

```bash
# Example placeholder if Dockerfile has test support
docker exec <container_id> pytest
```

---

## 📝 Final Remarks

- 🔄 Built for continuous delivery and integration  
- 🧪 Reliable with Pytest for unit testing  
- 🐋 Runs anywhere thanks to Docker  
- 🚦 Jenkins-ready for robust automation  

---
