# mhzssk
testdock8s
hello-world!
设置 -e

＃查看https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-init/中的版本
＃搜索“没有互联网连接运行kubeadm”
＃如果没有互联网连接运行kubeadm，您必须预先选择所需版本的主映像：
KUBE_VERSION = v1.10.3
KUBE_PAUSE_VERSION = 3.1
ETCD_VERSION = 3.1.12
DNS_VERSION = 1.14.8

GCR_URL = k8s.gcr.io
ALIYUN_URL = registry.cn-shenzhen.aliyuncs.com / cookcodeblog

images =（kube-proxy-amd64：$ {KUBE_VERSION}
kube-scheduler-amd64：$ {KUBE_VERSION}
kube-controller-manager-amd64：$ {KUBE_VERSION}
kube-apiserver-amd64：$ {KUBE_VERSION}
pause-amd64：$ {KUBE_PAUSE_VERSION}
etcd-amd64：$ {ETCD_VERSION}
k8s-dns-sidecar-amd64：$ {DNS_VERSION}
k8s-dns-kube-dns-amd64：$ {DNS_VERSION}
k8s-dns-dnsmasq-nanny-amd64：$ {DNS_VERSION}）


用于 imageName  在 $ {图像[@]}  ;  做
docker   pull $ ALIYUN_URL / $ imageName
docker   tag   $ ALIYUN_URL / $ imageName  $ GCR_URL / $ imageName
docker   rmi $ ALIYUN_URL / $ imageName
DONE

docker images
