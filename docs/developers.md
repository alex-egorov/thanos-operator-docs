---
title: Developers documentation
---


### Build & Push container
```
make docker-build IMG=banzaicloud/thanos-operator:latest
make docker-push IMG=banzaicloud/thanos-operator:latest
```

### Install operator the cluster
```
export KUBECONFIG="<kubeconfig location>"
make install
make deploy IMG=banzaicloud/thanos-operator:latest
```
