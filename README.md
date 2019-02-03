# flannel

拉取 quay.io 镜像

```shell
docker push kainonly/flannel:v0.11.0-amd64
// or
docker pull ccr.ccs.tencentyun.com/kainonly/flannel:v0.11.0-amd64
```

重命名镜像

```shell
docker tag kainonly/flannel:v0.11.0-amd64 k8s.gcr.io/flannel:v0.11.0-amd64
// or
docker tag ccr.ccs.tencentyun.com/kainonly/flannel:v0.11.0-amd64 k8s.gcr.io/flannel:v0.11.0-amd64
```