# Rhombix Technologies - Kubernetes Task

## Project Overview

This project demonstrates the deployment and management of a simple Nginx application using Kubernetes.

## Tools Used

- Docker Desktop
- Kubernetes
- kubectl
- Nginx

## Kubernetes Resources

### Deployment

Deployment name: `rhombix-k8s`

The deployment runs an Nginx container using the official Nginx Docker image.

### Service

Service name: `rhombix-k8s`

Service type: `LoadBalancer`

Port: `80`

## Tasks Completed

1. Enabled Kubernetes in Docker Desktop.
2. Verified the Kubernetes cluster using `kubectl cluster-info`.
3. Verified the Kubernetes node.
4. Created an Nginx deployment.
5. Verified the running Pod.
6. Exposed the deployment using a LoadBalancer service.
7. Accessed the application through the browser.
8. Scaled the deployment from 1 replica to 3 replicas.
9. Scaled the deployment back to 1 replica.
10. Created Kubernetes Deployment and Service YAML files.
11. Applied the YAML configurations successfully.

## Current Status

The Nginx application is successfully running on Kubernetes with one active replica.

## Author

Ibraheem Bin Khalid