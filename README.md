# 🚀 CI/CD Pipeline with Docker (Kalcer Coffee)

## 📖 Description
This project demonstrates a simple CI/CD (Continuous Integration & Continuous Deployment) pipeline using Docker and GitHub Actions.

The application is a static coffee shop website that is containerized using Docker. Any updates made to the project are automatically built and deployed through a CI/CD pipeline.

## 🎯 Objective
- Understand CI/CD workflow
- Learn Docker containerization
- Automate deployment process

## ⚙️ How It Works

1. Developer updates the project locally  
2. Changes are pushed to GitHub  
3. GitHub Actions triggers automatically  
4. Docker image is rebuilt  
5. Updated version is deployed  

## 🔄 Real Case (My Implementation)

In this project, I updated the website branding from:

- **"Kalcer Coffee" → "Sejiwa Coffee"**

Instead of manually editing files on the server, the update was done through Docker and automatically deployed via CI/CD pipeline.

### 💡 What This Proves
- Deployment is automated  
- No manual file upload needed  
- Changes are reflected instantly after pipeline runs  

## 🛠️ Tech Stack
- HTML, CSS, JavaScript  
- Docker  
- GitHub Actions  

## 🚀 How to Run Locally

### 1. Build Docker Image
```bash
docker build -t coffee-app .
```
### 2. Run Container
```bash
docker run -p 8080:80 coffee-app
```
## 📸 Output
<img width="2559" height="1470" alt="Project Screenshot" src="https://github.com/user-attachments/assets/91b3e3f8-30ac-49bf-9673-68eff87d864d" />

The output is a coffee shop landing page that updates automatically after each deployment.

## 📌 Notes

This project focuses on DevOps practices, specifically CI/CD automation and deployment workflow.

## 👨‍💻 Author

Affan Baihaqi

![CI/CD](https://img.shields.io/badge/CI/CD-Automated-success)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
