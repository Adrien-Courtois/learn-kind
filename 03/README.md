Cluster configuration with :
- ingress
- service
- deployment
```
kind create cluster --config clusterConfig.yaml
kubectl apply -k .
kubectl apply -f clusterDeployment.yaml
```

### Test
http://localhost/app
