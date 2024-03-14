
# Grafana Helm Chart

This Helm chart is used to install the Grafana web dashboarding system. It provides a convenient way to deploy and manage Grafana on Kubernetes.

## Get Repo Info

To use this Helm chart, you need to add the Grafana Helm repository to your local Helm installation. Run the following commands to add the repository and update it:

```bash
helm repo add grafana https://grafana.github.io/helm-charts
helm repo update
```

See [Grafana Helm Charts repository](https://grafana.github.io/helm-charts/) for command documentation.

## Installing the Chart

To install the chart with the release name `my-release`, run the following command:

```bash
helm install my-release grafana/grafana
```

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment, run the following command:

```bash
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
```
```

\