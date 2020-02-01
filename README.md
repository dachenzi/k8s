# kubernetes v1.17.2

kubernetes v1.17.2 image

```
docker login --username=287990400@qq.com registry.cn-shanghai.aliyuncs.com
hello2020

docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/coredns:1.6.5
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-apiserver:v1.17.2
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-scheduler:v1.17.2
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/etcd:3.4.3-0
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-controller-manager:v1.17.2
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/pause:3.1
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/flannel:v0.11.0-amd64
docker pull registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-proxy:v1.17.2

docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/coredns:1.6.5 k8s.gcr.io/coredns:1.6.5
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-apiserver:v1.17.2 k8s.gcr.io/kube-apiserver:v1.17.2
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-scheduler:v1.17.2 k8s.gcr.io/kube-scheduler:v1.17.2
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/etcd:3.4.3-0 k8s.gcr.io/etcd:3.4.3-0
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-controller-manager:v1.17.2 k8s.gcr.io/kube-controller-manager:v1.17.2
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/pause:3.1 k8s.gcr.io/pause:3.1
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/flannel:v0.11.0-amd64 quay.io/coreos/flannel:v0.11.0-amd64
docker tag registry.cn-shanghai.aliyuncs.com/mirrorsk8s/kube-proxy:v1.17.2 k8s.gcr.io/kube-proxy:v1.17.2
```
