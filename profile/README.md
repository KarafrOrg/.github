# [KarafrOrg](https://github.com/KarafrOrg)

GitHub organization for Homelab setup and related projects.

## Repositories

### ⎈ Reusable helm charts

| Repository                                                    | Description                                    |
|---------------------------------------------------------------|------------------------------------------------|
| [edge-access](https://github.com/KarafrOrg/edge-access)       | Allows access to services via internet         |
| [object-buckets](https://github.com/KarafrOrg/object-buckets) | Provisiones s3 compatble block storage buckets |

### 🏗️ Helm charts infrastructure

| Repository                                                        | Description                                                                    |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [infra-cicd](https://github.com/KarafrOrg/infra-cicd)             | Helm charts provisioning ci/cd infrastructure withing k8s cluster              |
| [infra-network](https://github.com/KarafrOrg/infra-network)       | Helm charts provisioning network infrastructure withing k8s cluster            |
| [infra-storage](https://github.com/KarafrOrg/infra-storage)       | Helm charts provisioning storage infrastructure withing k8s cluster            |
| [infra-secrets](https://github.com/KarafrOrg/infra-secrets)       | Helm charts provisioning secrets management infrastructure withing k8s cluster |
| [infra-monitoring](https://github.com/KarafrOrg/infra-monitoring) | Helm charts provisioning monitoring infrastructure withing k8s cluster         |

### 🌐 IAC for external infrastructure

| Repository                                                        | Description                                                                             |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| [infra-cloudflare](https://github.com/KarafrOrg/infra-cloudflare) | Terraform configuration for provisioning Cloudflare infrastructure                      |
| [infra-gcp](https://github.com/KarafrOrg/infra-gcp)               | Terraform configuration for provisioning [GCP](https://cloud.google.com) infrastructure |

## Important links

- [ArgoCD](https://argocd.karafra.net) - GitOps tooling for managing k8s cluster
- [Grafana](https://grafana.karafra.net) - Metrics and logs visualization
- [Cloudflare Dashboard](https://dash.cloudflare.com) - Cloudflare infrastructure management
- [Terraform cloud organization](https://app.terraform.io/app/karafrorg) - Terraform state management and collaboration
- [GCP Console](https://console.cloud.google.com) - GCP infrastructure management
