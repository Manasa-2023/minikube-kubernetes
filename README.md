# Minikube Kubernetes App

This project demonstrates deploying an nginx app to a local Kubernetes cluster using Minikube.

---

## Steps and Commands

### 1. Start Minikube
```bash
minikube start
2. Deploy the app
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
3. Check pods, deployments, and services
kubectl get pods
kubectl get deployments
kubectl get services
4. Scale the app
kubectl scale deployment myapp-deployment --replicas=4
kubectl get pods
kubectl get deployments
