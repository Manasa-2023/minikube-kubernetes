# Minikube Kubernetes App Deployment

This project demonstrates deploying and managing a simple **nginx** application on Kubernetes using **Minikube**.

---

## Steps to Run

### 1. Start Minikube
```bash
minikube start
### 2. Deploy the Application
```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
### 3. Check Resources
```bash
kubectl get pods
kubectl get deployments
kubectl get services
### 4. Scale the Application
```bash
kubectl scale deployment myapp-deployment --replicas=4
kubectl get pods
kubectl get deployments
