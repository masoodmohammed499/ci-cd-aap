# CI/CD Pipeline with GitHub Actions and AWS EC2

## Project Overview
This project demonstrates a complete CI/CD pipeline using GitHub Actions and AWS EC2.

## Technologies Used
- Node.js
- Git
- GitHub
- GitHub Actions
- AWS EC2
- PM2
- Ubuntu Linux

## Workflow
1. Developer pushes code to GitHub.
2. GitHub Actions triggers automatically.
3. GitHub Actions connects to EC2 using SSH.
4. Latest code is pulled from GitHub.
5. Dependencies are installed.
6. PM2 restarts the application.
7. Updated application is deployed automatically.

## Features
- Automated deployment
- Continuous Integration
- Continuous Delivery
- Zero manual deployment steps
