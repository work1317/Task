# Medusa Backend Deployment with Terraform + GitHub Actions

This project demonstrates Infrastructure-as-Code deployment of the Medusa open-source backend to AWS ECS Fargate using Terraform, with automated CI/CD via GitHub Actions.

## 🧰 Tech Stack
- AWS ECS Fargate
- Terraform
- GitHub Actions
- Docker (medusajs/medusa)

## 📦 How It Works
- Terraform provisions VPC, Subnets, ECS Cluster, IAM, Task Definitions, and ECS Services.
- GitHub Actions pipeline auto-applies Terraform on every push to `main`.

## 📁 Structure
