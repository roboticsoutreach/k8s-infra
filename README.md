# k8s-infra

This repository is the authoritative source of our Kubernetes cluster manifests,
which are automatically deployed to the cluster by Flux.

Secrets are managed centrally with Hashicorp Vault. Access to this is granted
through Authentik on an as-needed basis.
