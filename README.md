# ci-cd-to-kubernetes
CI/CD PIPELINE TO KUBERNETES
This repository demonstrates an end-to-end CI/CD pipeline
that builds a Docker image and deploys it to a Kubernetes cluster.

# What This Project Shows
- Dockerized application
- GitHub Actions CI/CD
- Kubernetes Deployment & Service
- Horizontal Pod Autoscaling
- Production-ready structure

# CI/CD Flow
1. Code pushed to main branch
2. GitHub Actions builds Docker image
3. Image pushed to Docker Hub
4. Kubernetes manifests applied automatically

# Prerequisites
- Kubernetes cluster (Minikube / EKS / AKS / GKE)
- Docker Hub account
- kubectl configured
- GitHub secrets:
  - DOCKER_USERNAME
  - DOCKER_PASSWORD

# Deployment
kubectl apply -f k8s/

# Use Case
- Startup application deployment
- CI/CD and Kubernetes demonstrations
