# Updating kubectl Certificates

We are using [k3s](https://k3s.io/) for Kubernetes.

Over time, the node certificates will be renewed and it will be necessary to re-download them to the clients for use
with kubectl.

On the nodes, the certificates are in `/etc/rancher/k3s/k3s.yaml`. These need to be copied over to `~/.kube/config` (some renaming will be usually be needed).