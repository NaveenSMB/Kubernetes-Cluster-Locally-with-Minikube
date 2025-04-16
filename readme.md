CLI Commands,

Step 1: Deploy Your App
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

Step 2: Verify & Manage
kubectl get pods
kubectl get services
kubectl get deployments

Step 3: Scale Deployment
kubectl scale deployment nginx-deployment --replicas=4

Step 4: Describe for Logs/Debugging
kubectl describe deployment nginx-deployment
kubectl describe pod <pod-name>

Step 5: Access the App
minikube service nginx-service
