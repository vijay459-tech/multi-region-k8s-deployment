# Multi-Region Kubernetes Deployment on AWS & GCP

## Overview
This project demonstrates a **highly available, multi-region Kubernetes cluster** deployed across AWS EKS and GCP GKE using Terraform and automated CI/CD pipelines. It showcases cloud architecture, scalability, and observability for enterprise workloads.

## Tech Stack
- Cloud: AWS (EKS, VPC, S3, RDS), GCP (GKE, Cloud Storage, Cloud SQL)
- Kubernetes & Helm
- Infrastructure as Code: Terraform
- CI/CD: GitHub Actions / Jenkins
- Monitoring: Prometheus, Grafana, ELK Stack
- Automation: Python / Bash

## Features
- Multi-region deployment with high availability
- Auto-scaling microservices (250+ pods)
- Centralized monitoring & alerting
- CI/CD pipeline for automated deployments
- Cost optimization with Terraform best practices

## Architecture Diagram
![Architecture](./docs/architecture.png)

## Setup Instructions
1. Clone the repository  
2. Install Terraform, kubectl, Helm  
3. Configure cloud provider credentials (AWS/GCP)  
4. Deploy infrastructure:
```bash
cd infra
terraform init
terraform apply
