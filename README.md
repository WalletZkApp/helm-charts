# helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add mobagel  https://walletzkapp.github.io/helm-charts/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
mobagel` to see the charts.

To install the zkWallet-globals chart:

    helm install zkWallet-globals walletzkapp/zkWallet-globals

To uninstall the chart:

    helm delete zkWallet-globals


To install the zkWallet-globals chart:

    helm install user-service-environment walletzkapp/user-service-environment

To uninstall the chart:

    helm delete user-service-environment
