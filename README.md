# kubernetes镜像

[k8s离线安装工具](https://github.com/Orientsoft/kubekit)

### 镜像下载

```
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/etcd-amd64:3.2.24
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/etcd-amd64:3.2.24  k8s.gcr.io/etcd:3.2.24
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-apiserver-amd64:v1.12.3
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-apiserver-amd64:v1.12.3 k8s.gcr.io/kube-apiserver:v1.12.3
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-controller-manager-amd64:v1.12.3
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-controller-manager-amd64:v1.12.3 k8s.gcr.io/kube-controller-manager:v1.12.3
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-proxy-amd64:v1.12.3
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-proxy-amd64:v1.12.3 k8s.gcr.io/kube-proxy:v1.12.3
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-scheduler-amd64:v1.12.3
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/kube-scheduler-amd64:v1.12.3 k8s.gcr.io/kube-scheduler:v1.12.3
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/pause-amd64:3.1
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/pause-amd64:3.1 k8s.gcr.io/pause:3.1
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/coredns:1.2.2
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/coredns:1.2.2 k8s.gcr.io/coredns:1.2.2
docker pull registry.cn-hangzhou.aliyuncs.com/apm70plus/kubernetes-dashboard-amd64:v1.10.0
docker tag registry.cn-hangzhou.aliyuncs.com/apm70plus/kubernetes-dashboard-amd64:v1.10.0  k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.0
```
