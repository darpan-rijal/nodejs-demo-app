## Node.js CI/CD Demo

# Objective
Automate code deployment using GitHub Actions.

# Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker

# Workflow
1. Trigger on push to main
2. Checkout repository
3. Setup Node.js
4. Build Docker image
5. Push image to Docker Hub

# Project Structure

nodejs-demo-app/
├── app.js
├── Dockerfile
├── package.json
└── .github/workflows/main.yml

# Result
CI/CD pipeline runs automatically whenever code is pushed to the main branch.
