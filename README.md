# Forked from https://github.com/cloudflare/helm-charts.

# Cloudflare Helm Charts

### About
A convenient location to publish Cloudflare helm charts. 

### Setup
```bash
helm repo add cloudflare https://nexus-mods.github.io/cloudflared-helm-charts/
helm repo update
```

### Discovery
```bash
helm search repo cloudflare
```

### Contents

- `charts/cloudflare-tunnel`: Helm 3 chart using cloudflared best practices
