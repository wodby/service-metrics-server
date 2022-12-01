# Metrics server service

Used for HPA, optionally deployed as a part of monitoring or metrics stack

## Update

- Take manifests from https://github.com/kubernetes-sigs/metrics-server/releases
- Replace namespace from `kube-system` to `monitoring`
