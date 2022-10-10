# k8s-compatibility-matrix

| kubernetes | 1.22 | 1.23 | 1.24 |
|:---:|:---:|:---:|:---:|
| [kubespray](https://github.com/kubernetes-sigs/kubespray/releases) | 2.18 | - | - |
| [cert-manager](https://cert-manager.io/docs/installation/supported-releases/) | 1.7, 1.8 | 1.7, 1.8 | 1.8-1.10 |
| [ingress-nginx](https://github.com/kubernetes/ingress-nginx#support-versions-table) | 1.1.1 - 1.2 | 1.1.1 - 1.2 | 1.3-1.4 |
| [rook-ceph](https://rook.github.io/docs/rook/v1.9/ceph-upgrade.html) | 1.8, 1.9 | 1.8, 1.9 | 1.8, 1.9 |
| [topolvm](https://github.com/topolvm/topolvm#supported-environments) [helm](https://github.com/topolvm/topolvm/tree/main/charts/topolvm) | + | + | - |
| [prometheus stack (helm)](https://github.com/prometheus-community/helm-charts/blob/main/charts/kube-prometheus-stack/README.md#upgrading-chart) | + | + | + |
| [kured](https://github.com/weaveworks/kured#kubernetes--os-compatibility) | 1.9.* | 1.9.* | 1.10.* |
| [ingress monitor controller](https://github.com/pavel1337/IngressMonitorController/tree/support-k8s-1.22) | + | ? | ? |
| [rabbit mq operator](https://github.com/rabbitmq/cluster-operator#supported-versions) | from v1.12.1 | ? | ? |
