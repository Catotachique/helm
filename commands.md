## Add repository
helm repo add bitnami https://charts.bitnami.com/bitnami


## Install chart
helm install my-nginx bitnami/nginx --version 19.0.4


## Uninstall the Helm Release
helm uninstall <release name>

## Fetches metadata for a given release
helm get metadata <release name>

## Values file for a named release
helm get values <release name>


# K3S
#### Run the following command to set the KUBECONFIG environment variable:
export KUBECONFIG=/etc/rancher/k3s/k3s.yaml

#### Alternatively, you can copy the kubeconfig to the default location (~/.kube/config):
sudo cp /etc/rancher/k3s/k3s.yaml ~/.kube/config