# Terraform 

Need to run seperately until we automate deployment from end-to-end.

### GKE

Stands up the GKE Cluster

```terraform apply```

### Helm-Consul

Helm installs consul on GKE - assumes you are `kubectl config` context set and you are authenticated to cluster

```./gke-consul-helm.sh```

### Helm-Vault-Wetty

Helm installs vault and wetty inside student K8s pod

```pod-deployments\terraform apply```

### Helm-Wetty


Helm installs vault inside student K8s pod

```terraform apply```


