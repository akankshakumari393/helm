## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add <alias> https://akankshakumari393.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  

You can use the `helm search` command to look for charts in this repo.

```console
helm search repo <alias> 
```

To install the a particular chart from this repo:

```console
helm install my-<chart-name> <alias>/<chart-name>
```
To uninstall the chart:

```console
helm uninstall my-<chart-name>
```
