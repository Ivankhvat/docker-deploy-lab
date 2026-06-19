# docker-deploy-lab

# Docker Deploy Lab
CI/CD laboratory project using GitHub Actions and Docker.

## Architecture

GitHub
   ↓
GitHub Actions
   ↓
Ubuntu Server
   ↓
Docker Compose
   ↓
Nginx Container

## Technologies
- Ubuntu Server
- Docker
- Docker Compose
- GitHub Actions
- Nginx
- Git

## Implemented
- Docker Compose validation
- GitHub Actions workflow
- CI pipeline
- Automated syntax checks

## Project Structure
docker-deploy-lab
├── docker-compose.yml
├── html
│   └── index.html
└── .github
    └── workflows
        └── deploy.yml

## Workflow

Every push to the main branch triggers:

1. Repository checkout
2. Docker Compose validation
3. CI pipeline execution
