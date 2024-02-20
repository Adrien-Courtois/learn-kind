Cluster configuration with :
- ingress
- service
- deployment
- autoscaling
```
kind create cluster --config clusterConfig.yaml
kubectl apply -k .
kubectl apply -f clusterDeploymentHPA.yaml
```

### Test
http://localhost/appv2
