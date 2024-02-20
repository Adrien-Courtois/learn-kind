Cluster configuration with :
- ingress
- service
```
kind create cluster --config clusterConfig.yaml
kubectl apply -k .
kubectl apply -f clusterServiceIngress.yaml
```