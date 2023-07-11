# k8s-compatibility-matrix

| kubernetes | 1.22 | 1.23 | 1.24 | 1.25 | 1.26 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| [kubespray](https://github.com/kubernetes-sigs/kubespray/releases) * | 2.18 | 2.19 | 2.20 | 2.21 | 2.22 |
| [cert-manager](https://cert-manager.io/docs/installation/supported-releases/) | 1.5-1.12 | 1.7-1.12 | 1.8-1.12 | 1.10-1.12 | 1.10-1.12 |
| [ingress-nginx](https://github.com/kubernetes/ingress-nginx#supported-versions-table) | 1.0 - 1.4 | 1.1.1 - 1.6.4 | 1.3.0 - 1.8.0 | 1.4.0 - 1.8.0 | 1.6.4 - 1.8.0 | 
| [rook-ceph](https://rook.github.io/docs/rook/v1.9/ceph-upgrade.html) | + | + | + | + | + | 
| [topolvm](https://github.com/topolvm/topolvm#supported-environments) [helm](https://github.com/topolvm/topolvm/tree/main/charts/topolvm) | 0.11-0.16 <br /> (5.0.0-11.0.0) | 0.14-0.17 <br /> (8.0.0-11.0.1) | 0.16-0.19 <br /> (11.0.0-11.2.1) | 0.17-0.19 <br /> (11.0.1-11.2.1) | 0.19 <br /> (11.2.1) |
| [prometheus stack (helm)](https://github.com/prometheus-community/helm-charts/blob/main/charts/kube-prometheus-stack/README.md#upgrading-chart) | + | + | + | > 40 | > 40 |
| [kured](https://kured.dev/docs/installation/#kubernetes--os-compatibility) | 1.8-1.10 | 1.9-1.11 | 1.10-1.12 | 1.11-1.13 | 1.12-1.13
| [ingress monitor controller](https://github.com/pavel1337/IngressMonitorController/tree/support-k8s-1.22) | + | ? | ? | ? | ? 
| [rabbit mq operator](https://github.com/rabbitmq/cluster-operator#supported-versions) | + | + | + | + | + |

* refers to default version
