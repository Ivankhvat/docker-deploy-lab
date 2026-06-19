# 🚀 Docker Deploy Lab

CI/CD laboratory project demonstrating automated Docker deployment using GitHub Actions.

---

## 📋 Project Overview

This project demonstrates a complete CI/CD workflow:

- Source code stored in GitHub
- Automatic workflow execution via GitHub Actions
- Docker Compose validation
- Nginx container deployment
- Automated pipeline checks

---

## 🏗 Architecture

Developer
    │
    ▼
 Git Push
    │
    ▼
 GitHub Repository
    │
    ▼
 GitHub Actions
    │
    ▼
 Docker Compose Validation
    │
    ▼
 Container Deployment
    │
    ▼
 Nginx Service

---

## ⚙️ Technologies

| Category | Technology |
|-----------|-----------|
| OS | Ubuntu Server |
| Containerization | Docker |
| Orchestration | Docker Compose |
| CI/CD | GitHub Actions |
| Web Server | Nginx |
| Version Control | Git |

---

## 📂 Repository Structure

docker-deploy-lab
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── html/
│   └── index.html
│
├── docker-compose.yml
│
└── README.md

---

## 🔄 CI/CD Workflow

Pipeline stages:

1. Checkout repository
2. Validate Docker Compose syntax
3. Verify deployment files
4. Execute workflow
5. Report pipeline status

---

## ✅ Implemented Features

- GitHub Repository Management
- Docker Compose Configuration
- GitHub Actions Workflow
- CI/CD Pipeline
- Automated Validation
- Nginx Container Deployment

---

## 📈 Skills Demonstrated

- Linux Administration
- Docker
- Docker Compose
- Git
- GitHub Actions
- CI/CD
- YAML
- Nginx
- Troubleshooting

---

## 🎯 Learning Outcomes

During this project I practiced:

- Creating GitHub Actions workflows
- Building CI/CD pipelines
- Docker container deployment
- Infrastructure automation
- Pipeline troubleshooting

---

## 📊 Project Status

✅ Completed

Current pipeline status: Passed
