# Renewing Contour Certifiecates on DNS Servers

The Contour certs used by Knative on the DNS Servers will expire after one year.

If they are expired, the rclone service will fail, eg:

* `rclone ls minikube11-proxy:`

To check the age:

* `kubectl -n contour-internal get secret`
* `kubectl -n contour-external get secret`

To regenerate:

* `kubectl -n contour-external delete secret contourcert`
* `kubectl -n contour-external delete secret envoycert`
* `kubectl -n contour-internal delete secret contourcert`
* `kubectl -n contour-internal delete secret envoycert`
* use the ArgoCD web console, search for the `<cluster-name>-knative` app, and delete the two `contour-certgen-v1-26-1` jobs, then re-sync.