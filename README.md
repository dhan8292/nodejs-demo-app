# Node.js Demo App - CI/CD with GitHub Actions

## 📌 Objective
Automate code deployment using GitHub Actions and Docker.

## 🛠️ Tools
- GitHub
- GitHub Actions
- Node.js v20
- Docker & DockerHub

## 🚀 Pipeline Flow
1. **Trigger**: Push to `main`
2. **Jobs**:
   - Checkout code
   - Install dependencies
   - Run tests
   - Build Docker image
   - Push image to DockerHub
3. **Deploy**: Pull image and run container

## 📂 Rnodejs-demo-app/
├── app.js
├── package.json
├── Dockerfile
└── .github/workflows/main.yml

Code

## 🔑 Setup
- Add secrets: `DOCKER_USERNAME`, `DOCKER_PASSWORD`
- Push code → pipeline runs automatically

## ✅ Deliverables
- GitHub repo with workflow
- DockerHub image
- Running container on server
