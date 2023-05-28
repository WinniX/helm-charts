## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add web-app https://winnix.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
web-app` to see the charts.

To install the web-app chart:

```
helm install my-web-app web-app/web-app
```

To uninstall the chart:

```
helm delete my-web-app
```
