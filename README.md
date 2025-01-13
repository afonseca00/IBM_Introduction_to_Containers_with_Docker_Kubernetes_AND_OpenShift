# IBM_Introduction_to_Containers_with_Docker_Kubernetes_AND_OpenShift

## Description

This repository contains projects and assignments completed as part of the IBM course "Introduction to Containers with Docker, Kubernetes, and OpenShift". The course covers various tools and concepts related to containerization, deployment, scaling, and management using Docker, Kubernetes, and OpenShift.

### Course Overview

The "Introduction to Containers with Docker, Kubernetes, and OpenShift" course provided a comprehensive understanding of containerization technology. Throughout the course, I learned about:
- The basics of Docker, including how to create, manage, and deploy containers.
- Kubernetes fundamentals, including creating and managing deployments, pods, and services.
- Advanced Kubernetes features like ConfigMaps, Secrets, and Persistent Volume Claims (PVCs).
- Implementing autoscaling and rolling updates for applications.
- OpenShift basics and how it integrates with Kubernetes for enhanced container orchestration.

## Contents

- [Practice Project](#practice-project)
- [Final Project](#final-project)

## Practice Project

### Description

In the Practice Project, I learned how to build and deploy a JavaScript application to Kubernetes using Docker. Additionally, I explored how to create and manage ConfigMaps, DaemonSets, Kubernetes Services, Secrets, Volumes, and Persistent Volume Claims (PVCs) for my application.

### Objectives

1. Build and deploy a JavaScript application to Kubernetes using Docker.
2. Create and understand ConfigMaps to manage configuration data.
3. Create DaemonSets to ensure that a pod runs on each node in the cluster.
4. Create Kubernetes Services to expose the application within the cluster.
5. Create Secrets to securely store sensitive information.
6. Define Volumes and Persistent Volume Claims (PVCs) to provide storage for the application.

### Step-by-Step Guide

For a detailed step-by-step guide, refer to the [Practice Project README](Practice_Project/README.md).

## Final Project

### Description

In the Final Project, I built and deployed a simple Guestbook application using Docker and Kubernetes. The application consists of a web front end where you can enter any text and submit it. I created Kubernetes Deployments and Pods for the application, applied Horizontal Pod Scaling, and performed Rolling Updates and Rollbacks.

### Objectives

1. Build and deploy a Guestbook application using Docker and Kubernetes.
2. Autoscale the Guestbook application using Horizontal Pod Autoscaler.
3. Perform Rolling Updates and Rollbacks on the Guestbook application.

### Step-by-Step Guide

For a detailed step-by-step guide, refer to the [Final Project README](Final_Project/README.md).

### Screenshots

Throughout the project, screenshots were taken to document the progress and verify the successful completion of tasks. These screenshots include:

- `crimages.png`: Screenshot of the Docker images pushed to IBM Cloud Container Registry.
- `app.png`: Screenshot of the deployed Guestbook application.
- `hpa.png`: Screenshot of the Horizontal Pod Autoscaler.
- `hpa2.png`: Screenshot showing the increase in replicas due to autoscaling.
- `upguestbook.png`: Screenshot of the updated Guestbook application image.
- `deployment.png`: Screenshot of the deployment details after applying updates.
- `up-app.png`: Screenshot of the updated Guestbook application.
- `rev.png`: Screenshot of the revision details of the deployment.
- `rs.png`: Screenshot of the replica sets after rollback.

## Conclusion

This repository contains comprehensive projects that helped me understand essential concepts and practices related to Docker, Kubernetes, and OpenShift. By completing these projects, I gained hands-on experience in building, deploying, scaling, and managing containerized applications.

