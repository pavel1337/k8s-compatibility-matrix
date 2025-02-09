# k8s-compatibility-matrix

| kubernetes | 1.31 | 1.32
|:---:|:---:|:---:
| [kubespray](https://github.com/kubernetes-sigs/kubespray/releases) * | 2.27 | 2.27
| [cert-manager](https://cert-manager.io/docs/installation/supported-releases/) | 1.16-1.17 | 1.17
| [ingress-nginx](https://github.com/kubernetes/ingress-nginx#supported-versions-table) | 1.12 | 1.12
| [rook-ceph](https://rook.io/docs/rook/latest-release/Getting-Started/Prerequisites/prerequisites/) | 1.15-1.16 | 1.16
| [topolvm](https://github.com/topolvm/topolvm#supported-environments) [helm](https://github.com/topolvm/topolvm/tree/main/charts/topolvm) | 0.36.1 <br /> (15.5.1)  | ?
| [prometheus stack (helm)](https://github.com/prometheus-community/helm-charts/blob/main/charts/kube-prometheus-stack/README.md#upgrading-chart) | 0.14 |  ?
| [kured](https://kured.dev/docs/installation/#kubernetes--os-compatibility) | 1.17.0 | ?
| [ingress monitor controller](https://github.com/pavel1337/IngressMonitorController/tree/support-k8s-1.22) | ? | ?
| [moco mysql](https://github.com/cybozu-go/moco?tab=readme-ov-file#supported-software) | 0.25.1 | ?
| [zalando postgres](https://github.com/zalando/postgres-operator?tab=readme-ov-file#supported-postgres--k8s-versions) | v1.14.0 | v1.14.0

* refers to default **version**
