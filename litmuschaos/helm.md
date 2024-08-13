$ kubectl config current-context
$ kubectl config get-contexts
$ kubectl config use-context docker-desktop
$ kubectl cluster-info
$ kubectl config view


$ helm repo add litmuschaos https://litmuschaos.github.io/litmus-helm/
$ helm install litmus-portal litmuschaos/litmus



% $ kubectl config set-cluster my-cluster --server=https://1.2.3.4
% $ kubectl config set-context my-context --cluster=my-cluster --user=my-user
% $ kubectl config set-credentials my-user --token=my-token