<p align="center">
  <img src="./static/helm-chart-logo.svg" height="220" width="220">
</p>

A helm repository that has a variety of helm charts for helping people to deploy stack inside Kubernetes cluster with best and security practices. One of the main motives of creating these charts is that person can easily deploy the stack or application inside the Kubernetes cluster without getting into the complexity.

[Helm](https://helm.sh/) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```shell
helm repo add ot-helm https://ot-container-kit.github.io/helm-charts
```

You can then run `helm search repo ot-helm` to see the charts.

### Helm Charts List

Currently supported helm charts are:-

- [Redis Operator](./charts/redis-operator)
- [Redis Setup](./charts/redis-setup)
- [K8s Vault Webhook](./charts/k8s-vault-webhook)
