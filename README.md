# End-to-End CI/CD and GitOps Pipeline for Cloud-Native Application

This project demonstrates the design and implementation of a **complete CI/CD pipeline**, integrating build, test, security, and deployment workflows for a cloud-native application.

## Overview

Built a fully automated development and deployment workflow using:

- GitHub Actions (CI/CD)
- Docker (containerization)
- Kubernetes (deployment)
- Flux (GitOps)
- Python (backend)

## Key Features

### Development Environment
Configured a reproducible dev environment using devcontainers, mise, and automated setup scripts.

### Build & Optimization
Built and optimized backend and frontend container images.

### Code Quality & Standards
Implemented:
- Ruff linter  
- Conventional commits with Commitizen  

### Security Scanning
Integrated Trivy to scan container images for vulnerabilities.

### Testing & Coverage
Added unit tests and coverage for the backend application.

### CI/CD Automation
- Implemented backend and frontend CI pipelines  
- Automated release creation  
- Automated pull requests for version updates  

### GitOps Deployment
- Created Kubernetes manifests  
- Integrated Flux for GitOps-based deployments  
- Added scripts for cluster bootstrapping and deployments  

### End-to-End Testing
Executed integration tests using k3d and Python to validate deployments.

## Outcome

- Built a **fully automated CI/CD pipeline**  
- Integrated **security, testing, and release automation**  
- Enabled **GitOps-driven Kubernetes deployments**  
- Established **production-ready DevOps workflows**
## Tech Stack

GitHub Actions, Docker, Kubernetes, Flux, Python, Trivy, Ruff, k3d, DevContainers
