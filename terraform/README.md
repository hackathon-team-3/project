# Terraform 

Need to run seperately until we automate deployment from end-to-end.

### GKE

Stands up the GKE Cluster

```terraform apply```

### Helm-Consul

Helm installs consul on GKE - assumes you are `kubectl config` context set and you are authenticated to cluster

```./gke-consul-helm.sh```

### Helm-Student-Pod

Helm installs vault and wetty inside student K8s pod

```pod-deployments\terraform apply```

### Helm-Ingress

Helm installs wetty and nip.io entries

```terraform apply```


