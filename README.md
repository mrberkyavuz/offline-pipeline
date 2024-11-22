# Offline Pipeline

## Notes

```yaml
argocd-image-updater.argoproj.io/image-list: hello=localhost:8443/library/hello
argocd-image-updater.argoproj.io/hello.update-strategy: newest-build
argocd-image-updater.argoproj.io/write-back-method: git
```

## References

- https://artifacthub.io/packages/helm/bitnami/gitea
- https://artifacthub.io/packages/helm/argo/argo-cd
- https://artifacthub.io/packages/helm/argo/argocd-image-updater
- https://github.com/goharbor/harbor-helm