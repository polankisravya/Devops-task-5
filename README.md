# DevOps Task 5 - Kubernetes Deployment with Minikube

## Steps to Run

1. Start Minikube:
   ```bash
   minikube start --driver=docker
   ```

2. Apply the Deployment:
   ```bash
   kubectl apply -f deployment.yaml
   ```

3. Apply the Service:
   ```bash
   kubectl apply -f service.yaml
   ```

4. Access the Application:
   ```bash
   minikube service nginx-service
   ```

This will open the deployed Nginx application in your browser.
