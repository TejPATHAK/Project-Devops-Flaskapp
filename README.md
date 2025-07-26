
# DEVOPS-PROJECT-1-FLASKAPP-

*Streamlining Deployment, Empowering Continuous Innovation*

![Last Commit](https://img.shields.io/badge/last%20commit-today-brightgreen)
![Python](https://img.shields.io/badge/python-85.4%25-blue)
![Languages](https://img.shields.io/badge/languages-2-informational)

---

## 🔧 Built with

![Flask](https://img.shields.io/badge/-Flask-black?logo=flask)
![Markdown](https://img.shields.io/badge/-Markdown-black?logo=markdown)
![Jenkins](https://img.shields.io/badge/-Jenkins-red?logo=jenkins)
![Pytest](https://img.shields.io/badge/-Pytest-blue?logo=pytest)
![Docker](https://img.shields.io/badge/-Docker-blue?logo=docker)
![Python](https://img.shields.io/badge/-Python-blue?logo=python)

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
---

## 🧠 Overview

**Devops-Project-1-Flaskapp** is a toolkit that simplifies the deployment, management, and monitoring of Flask applications within containerized environments. It integrates Docker, Jenkins, and Pytest to ensure scalable and automated workflows.

### Why use this?

- 🧩 **Containerization**: Consistent deployment environments.
- 🚀 **CI/CD Automation**: Jenkins pipelines for build/test/deploy.
- 📊 **Health Endpoints**: `/health`, `/metrics`, `/logs`.
- ⚙️ **Centralized Config**: Easy config management.
- 📄 **Logging**: Simple and centralized.

---

## 🚀 Getting Started

### 🧱 Prerequisites

Make sure you have:

- Python 3+
- pip
- Docker
- Jenkins (optional for CI/CD)

---

## 📥 Installation

### Clone the Repo

```bash
git clone https://github.com/priyam930/Devops-Project-1-Flaskapp-
cd Devops-Project-1-Flaskapp-
```

### Docker Build

```bash
docker build -t devops-flask-app .
```

### Local Run

```bash
pip install -r requirements.txt
python app.py
```

---

## ▶️ Usage

### Docker Run

```bash
docker run -p 5000:5000 devops-flask-app
```

### Flask App Endpoints

- `/`: Hello World
- `/health`: App status
- `/metrics`: App performance
- `/logs`: Access log output

---

## ✅ Testing

Run with:

```bash
pytest test_app.py
```

Run tests inside Docker (if defined):




---

## 🏁 Final Notes

- 📦 Easily deployable Flask microservice.
- 🧪 Tested with Pytest.
- 🐳 Containerized for portability.
- 🔄 CI/CD ready with Jenkins.

---

⬆️ [Return to Top](#devops-project-1-flaskapp-)
