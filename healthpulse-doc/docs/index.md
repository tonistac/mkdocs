# HealthPulse Portal

---

## Team Devius

---

### Team Members

| Team Member | Role          | email                  |
| ----------- | ------------- | ---------------------- |
| **Kamsi**   | Team Lead     | Uwah14@outlook.com     |
| **CJ**      | Ast Team Lead | dokes3@live.com        |
| **Emeka**   | Team Member   | emyugwu2021@gmail.com  |
| **George**  | Team Member   | geeone2002@yahoo.com   |
| **Kene**    | Team Member   | chinekene@gmail.com    |
| **Victor**  | Team Member   | ifeanyimba17@gmail.com |

---

## Project Overview

HealthPulse Portal is a healthcare web application built using React and TypeScript. The platform allows patients to:

- View appointments
- Access lab results
- Manage medications
- Communicate with healthcare providers

| Item               | Detail                                     |
| ------------------ | ------------------------------------------ |
| **Application**    | HealthPulse Patient Portal                 |
| **Tech Stack**     | React 18, TypeScript, Vite, Tailwind CSS   |
| **Cloud Provider** | AWS (ECS Fargate, EKS, ALB, VPC, Route 53) |
| **CI/CD**          | GitLab CI                                  |
| **Monitoring**     | Datadog                                    |

---

## Current Challenges

The application is currently deployed manually:

1. Build is run locally (`npm run build`)
2. Files are transferred via SCP
3. Server is accessed via SSH to restart Nginx

This process:

- Takes ~45 minutes per deployment
- Is error-prone
- Has caused multiple production outages
- Has no automated testing, security scanning, or monitoring

---

## Project Goal

Team Devius is responsible for transforming this into a **modern DevOps system** using:

- CI/CD pipelines
- Docker containerization
- AWS infrastructure
- Monitoring and observability tools

---

## What We Are Building

- Automated CI/CD pipeline (GitLab CI)
- Containerized application using Docker
- Deployment to AWS (ECS/EKS)
- Monitoring with Datadog
- Security scanning with Snyk
- Code quality analysis with SonarQube

---

## Quick Links

- Dev Environment: http://localhost:8084
- Prod Docs: http://localhost:84

---
