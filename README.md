# Flask-App DevOps Portfolio

This is my DevOps project using Flask. It shows real skills in building, deploying, and managing apps.

---

## 📌 Project Overview

- **App Type:** Flask Web Application  
- **Purpose:** Show DevOps skills like Docker, CI/CD, and cloud deployment  
- **Tech Stack:** Python, Flask, Docker, GitHub Actions, Environment Variables  

---

## 🛠 Features / Skills Demonstrated

1. **Docker Containerization**
   - The app runs inside a Docker container.
   - `Dockerfile` and `docker-compose.yaml` included.
2. **CI/CD**
   - GitHub Actions automatically builds, tests, and can deploy the app.
   - Linting and test workflow included.
3. **Environment Management**
   - Uses `.env` for environment variables.
   - Example file `.env.example` provided.
4. **Cloud-Ready**
   - App can be deployed to AWS EC2, ECS, or any cloud provider.
5. **Optional Add-ons**
   - Can add Terraform or Ansible for infrastructure automation.
   - Monitoring with Prometheus/Grafana can be added.

---

## ⚡ Setup / Run Locally

1. **Clone the repo:**
\`\`\`bash
git clone https://github.com/sabhckr/Flask-app.git
cd Flask-app
\`\`\`

2. **Set environment variables:**
\`\`\`bash
cp .env.example .env
# Edit .env as needed
\`\`\`

3. **Run with Docker:**
\`\`\`bash
docker-compose up --build
\`\`\`

4. **Open in browser:**  
\`\`\`
http://localhost:5000
\`\`\`

---

## 🗂 Project Structure (Simple Diagram)

