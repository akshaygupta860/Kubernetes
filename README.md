# Kubernetes
Kubernetes Commands
List Pods
kubectl get pods

List Deployments:

kubectl get deployments

List Services:
kubectl get services

Deploy an image:
kubectl run spring-boot-example --image=gcr.io/$GOOGLE_CLOUD_PROJECT/spring-boot-example:v1 --port=8080

Expose Load Balancer:
kubectl expose deployment spring-boot-example --type=LoadBalancer

Scale deployments:
kubectl scale deployment spring-boot-example --replicas=3

Command to retrieve logs:
kubectl logs <POD_NAME>
