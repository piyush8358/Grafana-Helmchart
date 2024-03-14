# Grafana Helm Chart

This Helm chart is used to install the Grafana web dashboarding system. It provides a convenient way to deploy and manage Grafana on Kubernetes.

## What is Helm?

Helm is a package manager for Kubernetes that helps you manage, install, and upgrade applications on a Kubernetes cluster. It simplifies the process of deploying complex applications by packaging all the required Kubernetes resources into a single unit called a "chart."

## What is a Chart?

A Helm chart is a collection of files that describe a set of Kubernetes resources necessary to run a particular application or service. It includes YAML manifest files for deploying Kubernetes objects like deployments, services, persistent volume claims, etc., along with any necessary configuration or templates.

## How is Helm Chart Useful?

Using Helm charts provides several benefits:

- **Simplified Deployment**: Helm charts package all the required Kubernetes resources into a single unit, making it easy to deploy complex applications with a single command.

- **Reusability**: Helm charts can be shared and reused across different environments and projects, reducing duplication of effort and promoting best practices.

- **Versioning and Rollbacks**: Helm allows you to version your charts, making it easy to roll back to previous versions if needed.

- **Configuration Management**: Helm supports templating, allowing you to customize deployments based on different environments or requirements using values files.

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

This README provides an overview of Helm, Helm charts, and how they are useful in deploying applications on Kubernetes, along with instructions for using the Grafana Helm chart. Let me know if you need further information!