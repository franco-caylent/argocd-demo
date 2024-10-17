# argocd-demo

# Login to argo
```
argocd login argocd.test
```

# Add credentials for github private repositories
```
argocd repo add https://github.com/argoproj/argocd-example-apps --username something-ignored --password a-github-pat
```