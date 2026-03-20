KarafrOrg
GitHub organization for Homelab setup and related projects.
Repositories
<p align="left"><img src="https://img.shields.io/badge/Kubernetes-%23007ACC?logo=kubernetes&logoColor=white"> <img
        src="https://img.shields.io/badge/Terraform-%235835CC?logo=terraform&logoColor=white"> <img
        src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white"> <img
        src="https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white">
</p>
<h2> ⎈ Reusable helm charts </h2>
<table width="100%">
    <thead>
    <tr>
        <th>Repository</th>
        <th>Description</th>
        <th>ArtifactHub link</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td><a href="https://github.com/KarafrOrg/edge-access">edge-access</a></td>
        <td>Allows access to services via internet</td>
        <td><a href="https://artifacthub.io/packages/helm/edge-access/edge-access">edge-access/edge-access</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/object-buckets">object-buckets</a></td>
        <td>Provisions S3-compatible block storage buckets</td>
        <td>
            <a href="https://artifacthub.io/packages/helm/object-buckets/object-buckets">object-buckets/object-buckets</a>
        </td>
    </tr>
    </tbody>
</table>
<h2> 🏗️ Helm charts infrastructure </h2>
<table width="100%">
    <thead>
    <tr>
        <th>Repository</th>
        <th>Description</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-cicd">infra-cicd</a></td>
        <td>Helm charts provisioning CI/CD infrastructure within Kubernetes cluster</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-network">infra-network</a></td>
        <td>Helm charts provisioning network infrastructure within Kubernetes cluster</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-storage">infra-storage</a></td>
        <td>Helm charts provisioning storage infrastructure within Kubernetes cluster</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-secrets">infra-secrets</a></td>
        <td>Helm charts provisioning secrets management infrastructure within Kubernetes cluster</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-monitoring">infra-monitoring</a></td>
        <td>Helm charts provisioning monitoring infrastructure within Kubernetes cluster</td>
    </tr>
    </tbody>
</table>
<h2> 🌐 IaC for external infrastructure </h2>
<table width="100%">
    <thead>
    <tr>
        <th>Repository</th>
        <th>Description</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-cloudflare">infra-cloudflare</a></td>
        <td>Terraform configuration for provisioning <a href="https://www.cloudflare.com">Cloudflare</a> infrastructure
        </td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-gcp">infra-gcp</a></td>
        <td>Terraform configuration for provisioning <a href="https://cloud.google.com">GCP</a> infrastructure</td>
    </tr>
    </tbody>
</table>

<h2>🔗Useful links</h2>

<ul>
  <li><strong>ArgoCD</strong> → <a href="https://argocd.karafra.net">argocd.karafra.net</a></li>
  <li><strong>Grafana</strong> → <a href="https://grafana.karafra.net">grafana.karafra.net</a></li>
  <li><strong>Cloudflare</strong> → <a href="https://dash.cloudflare.com">dash.cloudflare.com</a></li>
  <li><strong>Terraform Cloud</strong> → <a href="https://app.terraform.io/app/karafrorg">app.terraform.io/app/karafrorg</a></li>
  <li><strong>GCP Console</strong> → <a href="https://console.cloud.google.com">console.cloud.google.com</a></li>
</ul>