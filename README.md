# DevOps Assignment – Two-Tier Web Application Deployment

## 🚀 Overview
This project demonstrates end-to-end DevOps practices by containerizing, testing, deploying, and operating a two-tier web application (Python FastAPI backend + Next.js frontend) on AWS using ECS Fargate, Terraform, GitHub Actions, and AWS native tools.

---

## 🧱 Project Structure

Devops-project1/
│
├── backend/ # Python FastAPI app
├── frontend/ # Next.js frontend app
├── terraform/ # Terraform code for AWS infra
├── .github/ # GitHub Actions CI/CD pipelines
└── README.md


---

## 🌿 Branching Strategy

| Branch | Purpose |
|--------|---------|
| `main` | Production-ready code, triggers deployment |
| `develop` | Integration branch for features and testing |
| `feature/*` | Feature-specific work, merged into develop via PR |

---

## 🔧 Tools & Technologies

- **Git & GitHub**
- **Docker** (multi-stage builds)
- **Terraform** (AWS: ECS, Fargate, ALB, Secrets Manager)
- **GitHub Actions** (CI/CD)
- **AWS CloudWatch** (Monitoring & Alerts)

---

## 📦 Deployment Targets

- **Backend**: ECS Fargate, exposed via ALB
- **Frontend**: ECS Fargate, exposed via ALB
- **Monitoring**: AWS CloudWatch Dashboards
- **Secrets**: AWS Secrets Manager

