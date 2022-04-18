# nifikop
Downloads and serves the NifiKop Helm Chart via HTTP.

## Helm

*A hosted Helm chart* is available. Use the following commands to use it. https://tablecheck-labs.github.io/nifikop/

```
helm repo add nifikop https://tablecheck-labs.github.io/nifikop/
helm upgrade --install nifikop https://tablecheck-labs.github.io/nifikop/
```

For local installations:

```
helm upgrade --install --namespace=kube-system nifikop ./helm/nifikop
```
