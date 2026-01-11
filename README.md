# Spring Boot CI/CD Lab (Archive)

> ⚠️ **ARCHIVED:** This repository is maintained for historical reference only. No future updates are planned.

## Overview
Comprehensive DevOps lab demonstrating the deployment of a Spring Boot application to multiple cloud platforms (AWS EKS, Azure AKS) using various CI/CD tools.

## Key Concepts
- **Containerization:** Dockerfile for building the Java application.
- **Jenkins Pipelines:**
  - `Jenkinsfile-K8S`: Deployment to Kubernetes.
  - Integration with AWS ECR (Elastic Container Registry).
- **Azure DevOps:** `azure-pipelines.yml` for building and deploying to Azure.
- **Kubernetes Manifests:**
  - `eks-deploy-from-ecr.yaml`: Deployment to AWS EKS.
  - `aks-deploy-from-acr.yaml`: Deployment to Azure AKS.
  - `manifests/`: Standard K8s resources (Service, Deployment).

## Usage
This repository served as a sandbox for testing multi-cloud CI/CD workflows in 2022-2024.
