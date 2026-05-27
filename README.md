# workload-1-k3s-argocd

GitOps repository for the workload-1 K3s cluster.

## Layout

- `bootstrap/`: root Argo CD Application.
- `cluster/`: AppProject and Argo CD Application manifests.
- `infrastructure/`: platform controllers and shared cluster configuration.
- `apps/`: application workloads only.
