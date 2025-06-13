# Azure Containers Practice

This repository contains hands-on practice and demos for working with **Azure Containers**, including **Azure Container Instances (ACI)**, **Azure Kubernetes Service (AKS)**, **Docker containers**, and **Azure Container Registry (ACR)**.

## 🚀 Project Goals

* Learn and experiment with containerization using Docker.
* Deploy containers to Azure using various services.
* Understand CI/CD workflows for containerized apps.
* Practice scaling, networking, and monitoring container workloads in Azure.

## 📦 Topics Covered

* Dockerfile creation and container image builds
* Azure Container Registry (ACR) push/pull
* Azure Container Instances (ACI) deployment
* Azure Kubernetes Service (AKS) setup and deployment
* Azure CLI and Bicep templates (if applicable)
* YAML configurations for Kubernetes
* CI/CD integration using GitHub Actions (optional)

## 📁 Folder Structure

```
azure-containers-practice/
├── docker/                  # Dockerfiles and local container setup
├── acr/                     # Scripts and notes for Azure Container Registry
├── aci/                     # Azure Container Instances practice
├── aks/                     # Kubernetes manifests and AKS practice
├── pipelines/               # CI/CD examples (GitHub Actions or Azure Pipelines)
├── bicep/                   # (Optional) Bicep templates for provisioning
└── README.md                # This file
```

## 🛠️ Prerequisites

* [Docker](https://www.docker.com/)
* [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
* An active Azure subscription
* (Optional) [kubectl](https://kubernetes.io/docs/tasks/tools/)

## 🧪 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/azure-containers-practice.git
   cd azure-containers-practice
   ```

2. Login to Azure:

   ```bash
   az login
   ```

3. Start with a folder (e.g., `docker/`) and follow the steps in its `README.md` or notes.

## 📘 References

* [Azure Container Instances Documentation](https://learn.microsoft.com/en-us/azure/container-instances/)
* [Azure Kubernetes Service Documentation](https://learn.microsoft.com/en-us/azure/aks/)
* [Docker Docs](https://docs.docker.com/)
* [Azure Container Registry Documentation](https://learn.microsoft.com/en-us/azure/container-registry/)
