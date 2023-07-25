# aria2 Helm Chart

- Installs the lightweight multi-protocol & multi-source command-line download utility -- [aria2](https://aria2.github.io/)。

## Get Repo Info

```console
helm repo add panghuli https://charts.panghuli.cn
helm repo update
```

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install my-release panghuli/aria2
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
