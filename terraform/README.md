# Terraform 

Need to run seperately until we automate deployment from end-to-end.

### gke

Stands up the GKE Cluster

```terraform apply```

### helm-consul

Helm installs consul on GKE - assumes you are `kubectl config` context set and you are authenticated to cluster

```./gke-consul-helm.sh```

### helm-student-pod

Helm installs vault and wetty inside student K8s pod

```pod-deployments\terraform apply```

### helm-ingress

Helm installs wetty and nip.io entries

```terraform apply```


