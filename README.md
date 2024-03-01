# AAP/AWX GitOps

## Requirements

- Kubernetes
    - Running Kubernetes cluster
    - `kubectl`
- [ArgoCD Autopilot](https://argocd-autopilot.readthedocs.io/en/stable/)

## Boostraping

```sh
export GIT_REPO=https://github.com/owner/installation-repo
export GIT_TOKEN=xxx

argocd-autopilot repo bootstrap --recover
```