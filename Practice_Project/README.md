# Kubernetes Practice Project

## Description

In this project, I learned how to build and deploy a JavaScript application to Kubernetes using Docker. Additionally, I explored how to create and manage ConfigMaps, DaemonSets, Kubernetes Services, Secrets, Volumes, and Persistent Volume Claims (PVCs) for my application.

## Objectives

1. Build and deploy a JavaScript application to Kubernetes using Docker.
2. Create and understand ConfigMaps to manage configuration data.
3. Create DaemonSets to ensure that a pod runs on each node in the cluster.
4. Create Kubernetes Services to expose my application within the cluster.
5. Create Secrets to securely store sensitive information.
6. Define Volumes and Persistent Volume Claims (PVCs) to provide storage for my application.

## Prerequisites

- Docker installed
- Kubernetes configured
- kubectl configured to communicate with the Kubernetes cluster
- Access to IBM Cloud Container Registry (or another container registry of your choice)

## Step-by-Step Guide

### 1. Building and Deploying the Application

Clone the repository containing the starter code:
```sh
git clone https://github.com/ibm-developer-skills-network/containers-project.git
cd containers-project/
