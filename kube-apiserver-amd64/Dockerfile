FROM gcr.io/google_containers/kube-apiserver-amd64:v1.9.6

DOCKER TAG registry.cn-beijing.aliyuncs.com/yayaya/kube_garage/kube-apiserver-amd64:v1.10.3 k8s.gcr.io/kube-apiserver-amd64:v1.10.3
# 查看镜像
docker images
# 删除新构建的镜像，只保留gcr.io镜像
docker rmi registry.cn-beijing.aliyuncs.com/yayaya/kube_garage/kube-apiserver-amd64:v1.10.3
# 再次查看镜像
docker images
