## Requirements ##
In order to collect the logs from all the nodes, first you need to add fluentd-pod.yml to `/etc/kubernetes/manifests` in all the nodes and reload kubelet service.
Nginx ingress controller must be configured to enable the ingress resource for kibana.