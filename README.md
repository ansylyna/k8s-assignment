# Kubernetes Workloads & Service Exposure

This project demonstrates Kubernetes concepts using a Dockerized Python Flask application.

## Features
- Deployment with multiple replicas
- Pod inspection and logs
- ClusterIP Service (internal communication)
- NodePort Service (external access)
- Scaling and self-healing
- StatefulSet with stable pod identity

## Technologies Used
- Kubernetes (Minikube)
- Docker
- Python Flask
- Ubuntu VM

## How to Run
1. Apply deployment:
   kubectl apply -f deployment.yaml

2. Apply service:
   kubectl apply -f service.yaml

3. Access using NodePort:
   kubectl get svc

## Author
ansy
