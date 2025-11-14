# DevOpsLab

# Argocd
Changes in the value files are for ingress:
```yaml
    annotations: {
      nginx.ingress.kubernetes.io/backend-protocol: "HTTPS",
      alb.ingress.kubernetes.io/ssl-passthrough: "true",
      nginx.ingress.kubernetes.io/force-ssl-redirect: "false"
    }
``` 