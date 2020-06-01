# k3d
```
k3d create cluster --publish 3000:80
```

# grafana
```
kc create -f ./grafana
```

# loki
```
helm repo add loki https://grafana.github.io/loki/charts
helm repo update
helm upgrade --install loki loki/loki-stack
```

# prometheus
```
kc create -f ./prometheus
```
