# Minikube Kubernetes App

This project runs an nginx app on Kubernetes using Minikube.

## Steps
1. Start Minikube  
 Command
 minikube start

2. Deploy the app
 Commands
 kubectl apply -f deployment.yaml
 kubectl apply -f service.yaml

3. Check pods, deployments, and services
 Commands
 kubectl get pods
 kubectl get deployments
 kubectl get services
 
4. Scale the app
 Commands
 kubectl scale deployment myapp-deployment --replicas=4
 kubectl get pods
 kubectl get deployments