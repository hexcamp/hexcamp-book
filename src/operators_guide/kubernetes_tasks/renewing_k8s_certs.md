# Renewing Kubernetes Certificates on DNS Servers

If the DNS servers have been running for a while, the Kubernetes certificates will expire.

More info:

* https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/troubleshooting-kubeadm/#kubelet-client-cert
* `kubeadm certs check-expiration`
* `kubeadm certs renew all`
* `kubeadm kubeconfig user --client-name admin`

After rotating keys, update local `~/.kube/config` and run `argocd cluster rm <node-name>` followed by `argocd cluster add <node-name>`.