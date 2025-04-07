## Add repository

helm repo add bitnami https://charts.bitnami.com/bitnami


## Install chart

helm install my-nginx bitnami/nginx --version 19.0.4





# K3S
#### Run the following command to set the KUBECONFIG environment variable:

export KUBECONFIG=/etc/rancher/k3s/k3s.yaml

#### Alternatively, you can copy the kubeconfig to the default location (~/.kube/config):

sudo cp /etc/rancher/k3s/k3s.yaml ~/.kube/config