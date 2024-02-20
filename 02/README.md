### Mise en place
Cluster configuration with :
- ingress
- service
```
kind create cluster --config clusterConfig.yaml
kubectl apply -k .
kubectl apply -f clusterServiceIngress.yaml
```

### Test
http://localhost/test
