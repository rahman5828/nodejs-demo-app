# Node.js CI/CD Pipeline Demo 🚀

This project is a simple Node.js web app deployed using Docker and GitHub Actions as part of a DevOps internship task.

## 📦 Technologies Used
- Node.js
- Express.js
- Docker
- GitHub Actions
- DockerHub

## 🛠 What This Project Does
- A minimal Node.js server using Express that returns a "Hello" message.
- Dockerfile builds the app into a Docker container.
- GitHub Actions automates the following pipeline:
  1. On push to `main` or `master` branch
  2. Builds the Docker image
  3. Pushes the image to DockerHub

## 🧪 How to Run Locally

```bash
git clone https://github.com/your-username/nodejs-demo-app.git
cd nodejs-demo-app
npm install
npm start
