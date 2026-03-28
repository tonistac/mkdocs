# CI/CD Pipeline

## Overview

The CI/CD pipeline automates the process of building, testing, and deploying the HealthPulse application.

---

## Pipeline Stages

### 1. Build
- Install dependencies
- Compile application
- Generate build artifacts

---

### 2. Test
- Run unit tests (Vitest)
- Run end-to-end tests (Playwright)

---

### 3. Code Quality
- Analyze code using SonarQube
- Ensure code coverage standards

---

### 4. Security Scan
- Scan dependencies using Snyk
- Identify vulnerabilities

---

### 5. Build Docker Image
- Build container using Dockerfile
- Tag and push image to registry

---

### 6. Deploy
- Deploy container to AWS ECS/EKS
- Configure load balancer

---

## Tools Used

- GitLab CI/CD
- Docker
- SonarQube
- Snyk
- AWS ECS/EKS

---