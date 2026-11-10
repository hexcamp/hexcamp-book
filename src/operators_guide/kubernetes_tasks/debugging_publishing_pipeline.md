# Debugging Publishing Pipeline

## GitHub Webhook for hexcamp-coredns-sites

* Check [GitHub WebHook settings](https://github.com/hexcamp/hexcamp-coredns-sites/settings/hooks)

If webhook deliveries are failing, try to remove and recreate listener in ArgoCD:

* [ArgoCD app: ryzen9-repair-sites-watcher](https://argocd2.infra.hex.camp/applications/ryzen9-repair-sites-watcher)
* Resource: [github-source-sites](https://github.com/hexcamp/hexcamp-argocd/blob/main/repair-pipeline/sites-watcher/github-source-sites.yaml)