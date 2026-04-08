<h1> 
    <a href="https://github.com/KarafrOrg">KarafrOrg</a>
</h1>
<p align="left">
    <img src="https://img.shields.io/badge/Kubernetes-%23007ACC?logo=kubernetes&logoColor=white"> 
    <img src="https://img.shields.io/badge/Terraform-%235835CC?logo=terraform&logoColor=white">
    <img src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white"> 
    <img src="https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white">
    <img src="https://img.shields.io/badge/OVH-0A2E5C?logo=ovh&logoColor=white">
</p>
GitHub organization for Homelab setup and related projects.
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
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-terraform">infra-terraform</a></td>
        <td>Terraform configuration for provisioning <a href="https://app.terraform.io/app/organizations">Terraform Cloud</a> resources</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-github">infra-github</a></td>
        <td>Terraform configuration for provisioning <a href="https://github.com">GitHub</a> resources</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-ovh">infra-ovh</a></td>
        <td>Terraform configuration for provisioning <a href="https://www.ovhcloud.com/en/">OVH</a> resources</td>
    </tr>
    <tr>
        <td><a href="https://github.com/KarafrOrg/infra-cluster">infra-cluster</a></td>
        <td>Ansible playbooks used for bootstrapping and managing k8s<a href="https://kubernetes.io">OVH</a> cluster</td>
    </tr>
    </tbody>
</table>

<h2> 🔗 Useful links</h2>
<ul>
  <li><a href="https://argocd.karafra.net">ArgoCD</a> - GitOps CI/CD engine</li>
  <li><a href="https://grafana.karafra.net">Grafana</a> - Metrics and logs visualization</li>
  <li><a href="https://dash.cloudflare.com">Cloudflare</a> - Infrastructure and DNS management</li>
  <li><a href="https://app.terraform.io/app/karafrorg">Terraform Cloud</a> - State management and collaboration</li>
  <li><a href="https://console.cloud.google.com">GCP Console</a> - Google Cloud infrastructure management</li>
  <li><a href="https://manager.ca.ovhcloud.com/#/dedicated-servers/server">OVH Console</a> - Bare metal servers</li>
</ul>