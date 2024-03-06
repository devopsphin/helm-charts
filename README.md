# Web Server Helm Chars

[![Helm Charts](https://github.com/devopsphin/helm-charts/actions/workflows/helm-chart-release.yaml/badge.svg?branch=main)](https://github.com/devopsphin/helm-charts/actions/workflows/helm-chart-release.yaml)

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```bash
helm repo add web-server https://devopsphin.github.io/helm-charts
helm repo update
```

### Install Nginx
```bash
helm install nginx web-server/web-server-nginx
```

### Uninstall Nginx
```bash
helm uninstall nginx
```

### Install Apache
```bash
helm install apache web-server/web-server-apache
```

### Uninstall Apache
```bash
helm uninstall apache
```
