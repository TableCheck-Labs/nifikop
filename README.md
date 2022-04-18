# nifikop
Downloads and serves the NifiKop Helm Chart via HTTP.

## Helm

*A hosted Helm chart* is available. Use the following commands to use it. https://tablecheck-labs.github.io/nifikop/index.yaml

```
helm repo add nifikop https://tablecheck-labs.github.io/nifikop/index.yaml
helm upgrade --install nifikop https://tablecheck-labs.github.io/nifikop/index.yaml
```

For local installations:

```
helm upgrade --install --namespace=kube-system nifikop ./helm/nifikop
```
