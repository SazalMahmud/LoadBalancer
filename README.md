1. To create the deployment and service, run the following commands:

kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml

 --------------Check the status of the deployment using:---------------
 kubectl get deployments
 
 kubectl get services

 2. We can access the Nginx server through any of our Kubernetes cluster external IP addresses.
    curl http:// External IP(ex10.62.2.195):8080

