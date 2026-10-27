# JonesGroup.AKS-Edge-Test

GitOps source for AKS Edge cluster `home-k3s-01`.

## Structure
- `clusters/home` - baseline workload manifests (Kustomize)

## Manual test
```bash
kubectl apply -k clusters/home
```
