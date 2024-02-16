# learn-kind
### Installation kind
```
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.22.0/kind-linux-amd64
chmod +x ./kind
sudo mv ./kind /usr/local/bin/kind
sudo apt-get install golang
```

### Créer un cluster
Création d'un cluster `à la volée`

```
kind create cluster
# ou
kind create cluster --name cluster-name
```
Ou via un fichier de configuration
```
kind create cluster --config clusterConfig.yaml
```

### Intéragir avec kind
Lister les clusters créés via kind
```
kind get clusters
```
Supprimer un cluster
```
kind delete cluster --name cluster-name
```
