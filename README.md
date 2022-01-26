# lab-k8s-postgresql

Deploy a postgreSQL DataBase in a minikube cluster

Run
---------------
- $kubectl apply -f postgres-configmap.yaml 
- $kubectl apply -f postgres-volume.yaml 
- $kubectl apply -f postgres-deployment.yaml
- $kubectl apply -f postgres-service.yaml
- $kubectl get cm
- $kubectl get pvc
- $kubectl get deployment
- $kubectl get svc
