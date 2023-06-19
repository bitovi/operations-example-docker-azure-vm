<!-- markdownlint-disable MD049 -->
<!-- spell-checker: disable -->
# BitOps Landscape

- BitOps Core

  - GitHub Open Source
  - Docker repo
  - `cli`

  - Documentation
  _consolidate/DRY_
    - [bitops.sh](https://bitops.sh)
    - Confluence (internal)
    - Confluence (public)
    - GitHub wiki/issues
    - Public Jira

  - Operations Repos
    - before/after scripts
    - bitops.config.yaml
  
- Surrounding Ecosystem
  _remove this branch?_

  - **Plugins**
    - Providers
      - AWS
        - **EC2**
        - **EKS**
      - GCP
        - *GCVM*
        - *GKE*
      - Azure
      - Digital Ocean
      - [Hetzner](https://www.hetzner.com/cloud)
      - minikube
      - kind
      - [Linode](https://www.linode.com/)
  
    - Tools
      - InfraAsCode
        - **Terraform**
        - **CloudFormation**
        - K8s Manifests
        - Rancher
        - VMware Tanzu
        - Provider clis
  
      - ConfigAsCode
        - **Ansible**
        - **Helm**
        - Skaffold
        - Chef
        - shell scripts
  
  - **Package Managers**
_should this go under plugins?_

    - Artifactory
    - [ProGet](https://inedo.com/proget)
    - GitHub Packages
    - AWS ECR
    - GCP Container Registry
    - bitnami
    - Helm Repos
    - Docker Hub

  - **Runners/Pipelines**
    - Jenkins
    - GitLab
    - **GitHub Actions**
    - [Dagger](https://dagger.io)
    - [Tekton](https://tekton.dev/)
    - `local`
    - Rancher Fleet
    - Harness
    - CircleCI
    - Azure DevOps (TFS)
    - BitOps Cloud

  - **GUI**
    - Platforms
      - [Argo](https://argoproj.github.io/)
      - Spinnaker
      - Harness
      - GitLab
      - Jenkins?

    - Operations Console
      - Dashboard
      - Pipeline Management
      - History
      - Observability
        - Monitoring
        - Logging
      - Tools
        - **Foresight**
