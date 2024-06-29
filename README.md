# ZeroAWS

**[READ THE BLOG for details](https://sl.audacioustux.com/eks-aws-playbook)**

## Overview

![Ref Arch - Draft](misc/draft-reference-arch.svg)

### Tools, Technologies and Topics covered

- Pulumi
- GitOps
- IaC
- DevContainers
- AWS
  - IAM
  - IAM Identity Center
  - Secrets Manager
  - RDS
    - Serverless v2 VS Aurora db class instance
    - Read/Write Split & Connection Pooling
  - VPC
    - NAT
    - IGW
    - Gateway Endpoints
    - VPC Peering
  - KMS
  - EBS
  - EFS
  - S3
  - EKS
    - Pod Identity
    - IRSA
    - Addons
    - Node Group
  - Route53
  - AWS Backup
  - ALB
  - NLB
- Kubernetes
  - CoreDNS
  - Kyverno
  - Cert Manager
  - External DNS
  - External Secrets
  - Argo CD
  - Cilium
    - VPC CNI Replacement
    - Kube-Proxy Replacement
    - Envoy L7
    - Gateway API
    - Hubble
  - Prometheus
    - Thanos
  - Grafana
  - Alert Manager
  - Loki
  - Promtail
  - Karpenter
  - Vertical Pod Autoscaler
  - Horizontal Pod Autoscaler
  - Keda
- Dragonfly
- Cloudnative-PG
- Minio
- Knative
- Argo Workflow
- Argo Events
- YugabyteDB
- Akka Clustering
