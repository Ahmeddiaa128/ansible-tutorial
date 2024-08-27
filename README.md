# ArgoCD Testing Project

This repository contains the necessary configurations to set up a test project in ArgoCD. The goal is to demonstrate the use of ArgoCD for deploying applications on a Kubernetes cluster.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [1. Install ArgoCD](#1-install-argocd)
  - [2. Create ArgoCD Project](#2-create-argocd-project)
  - [3. Deploy Application](#3-deploy-application)
- [Usage](#usage)
- [Clean up](#clean-up)

## Prerequisites

Before you start, ensure you have the following:

- A running Kubernetes cluster (Minikube, EKS, GKE, etc.)
- `kubectl` configured to interact with your cluster
- ArgoCD installed on the cluster
- A Git repository with application manifests (YAML files)
