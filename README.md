# Deployments for sample app

1. Apply staging app
```
$ kubectl -n argocd apply -f staging-app.yaml
```

2. Apply prod app
```
$ kubectl -n argocd apply -f prod-app.yaml
```