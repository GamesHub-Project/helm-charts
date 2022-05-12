# [helm-charts](https://github.com/GamesHub-Project/helm-charts)

# GamesHub Project Kubernetes Helm Charts

The code is provided as-is with no warranties.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add gameshub https://gameshub-project.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
gameshub` to see the charts.

To install the a specific chart:

    helm install <chart-name> gameshub/<chart-name>

To uninstall the chart:

    helm delete <chart-name>
    
    
## License

tbd
