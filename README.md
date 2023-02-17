# Prometheus_k8s
Kubernetes example for deployment of Prometheus alertmanager


kubectl apply -f prometheus-configmap.yaml

kubectl apply -f prometheus-deployment.yaml

kubectl apply -f prometheus-service.yaml

kubectl apply -f ingress.yaml

