# Helm Charts

[![Publish Charts](https://github.com/erumble/helm-charts/workflows/Publish%20Charts/badge.svg)](https://github.com/erumble/helm-charts/actions/workflows/helm-release.yaml)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add erumble https://erumble.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
erumble` to see the charts.

To install a chart:
```bash
helm install <release-name> erumble/<chart-name>
```

To uninstall the chart:
```bash
helm delete <release-name>
```
