# Minikube Kubernetes App Deployment

This project demonstrates deploying and managing a simple **nginx** application on Kubernetes using **Minikube**.

## Steps to Run
1. **Start Minikube**  
   `minikube start`

2. **Deploy the Application**  
   `kubectl apply -f deployment.yaml`  
   `kubectl apply -f service.yaml`

3. **Check Resources**  
   `kubectl get pods`  
   `kubectl get deployments`  
   `kubectl get services`

4. **Scale the Application**  
   `kubectl scale deployment myapp-deployment --replicas=4`  
   `kubectl get pods`  
   `kubectl get deployments`

## Files in This Repository
- `deployment.yaml` → Defines the nginx deployment.
- `service.yaml` → Exposes the nginx deployment as a service.

## Screenshots Included
- Pods before scaling
- Deployment details
- Service details
- Pods after scaling
- Nginx UI in browser

