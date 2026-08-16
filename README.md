# homelab

GitOps source of truth for the three-node k3s cluster.

  bootstrap/   root Application (app-of-apps) - applied manually, once
  apps/        Argo CD Application manifests, one per workload
  platform/    values files for third-party Helm charts
  charts/      first-party Helm charts
