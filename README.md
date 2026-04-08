# CI/CD Docker Deployment with GitHub Actions (WABA Backend)


## Project Overview
This project is a hands-on implementation of a CI/CD pipeline using GitHub Actions, Docker, and AWS EC2.

The main goal is to simulate a real-world deployment workflow:
- Automatically build and push Docker images
- Deploy updates to a remote EC2 server
- Notify deployment status via Telegram

A simple backend service integrating basic WhatsApp Business API (WABA) features is included as a sample application to support the CI/CD workflow.

## ⚙️ Tech Stack

- Backend: Node.js (Express)
- CI/CD: GitHub Actions
- Containerization: Docker
- Deployment: AWS EC2
- Registry: GitHub Container Registry (GHCR)
- Notification: Telegram Bot API

## Workflow of CI/CD pipeline
Developer Push → GitHub Actions → Build Docker Image → Push to GHCR → SSH to EC2 and Pull → Run Container → Telegram Notification
                                                   
