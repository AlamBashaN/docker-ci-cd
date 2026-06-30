# 🚀 Docker CI/CD with GitHub Actions

Automated Docker image build and push workflow using GitHub Actions and Docker Hub.

## 📌 Overview

This project demonstrates how to automate Docker image building and publishing using GitHub Actions. Every time code is pushed to the main branch, the workflow automatically builds a Docker image and pushes it to Docker Hub.

## ✨ Features

- Automated CI/CD pipeline using GitHub Actions
- Docker image build automation
- Pushes images to Docker Hub
- Simple HTML application deployment
- Easy to extend for real-world projects

## 🛠️ Tech Stack

- Docker
- GitHub Actions
- Docker Hub
- HTML

## 📁 Project Structure

```
docker-ci-cd/
│── .github/
│   └── workflows/
│       └── docker-ci-cd.yml
│── Dockerfile
│── index.html
└── README.md
```

## ⚙️ Workflow

1. Push code to the `main` branch.
2. GitHub Actions workflow is triggered.
3. Docker image is built automatically.
4. Image is pushed to Docker Hub.
5. Ready for deployment.

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/AlamBashaN/docker-ci-cd.git
cd docker-ci-cd
```

### Build Docker Image

```bash
docker build -t docker-ci-cd .
```

### Run Container

```bash
docker run -d -p 8080:80 docker-ci-cd
```

Open your browser:

```
http://localhost:8080
```

## 📷 Output

The project serves a simple HTML page from a Docker container.

## 🎯 Learning Objectives

- Understand Docker image creation
- Learn GitHub Actions workflows
- Automate Docker image builds
- Push images to Docker Hub
- Implement basic CI/CD practices

## 👨‍💻 Author

**Alam Basha N**

- GitHub: https://github.com/AlamBashaN

---

⭐ If you found this project helpful, consider giving it a Star!
