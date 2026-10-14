# Muhammad Jaffar

**DevOps & Platform Engineer**
Lahore, Pakistan · [jaffar.devops052@gmail.com](mailto:jaffar.devops052@gmail.com) · +92 320 9452558

---

## Summary

DevOps and Platform Engineer with 1.5+ years of experience designing, automating, and operating production-grade AWS infrastructure. Core work includes private EKS clusters provisioned with Terraform, zero-trust workload identity through IRSA and OIDC, GitOps delivery with ArgoCD, and end-to-end observability with Prometheus and Grafana. Focused on reliability engineering, security, and measurable delivery improvements.

## Core Competencies

- **Cloud (AWS):** EKS, ECS Fargate, ECR, VPC, IAM, IRSA, OIDC, RDS, S3, ALB, CloudFront, Route 53, CloudWatch, Secrets Manager
- **Infrastructure as Code:** Terraform (modules, remote state with S3 and locking, workspaces), Helm, Helmfile
- **Containers & Orchestration:** Docker, Kubernetes, RBAC, HPA, NetworkPolicies, EBS CSI driver
- **CI/CD & GitOps:** ArgoCD, Jenkins (agents on Kubernetes), GitHub Actions, rolling, blue-green, and canary deployments
- **Observability:** Prometheus, Grafana, Loki, Promtail, Jaeger, Alertmanager
- **Security:** IRSA, OIDC, External Secrets Operator, Trivy, SonarQube, least-privilege IAM

## Selected Projects

### CloudNative Platform — Internal Developer Platform on Kubernetes
Reference implementation of a platform engineering environment: Istio service mesh, ArgoCD GitOps delivery, GitHub Actions CI/CD with Trivy and SonarQube quality gates, and RBAC with NetworkPolicy isolation. Designed to run entirely locally using Kind and LocalStack.

### Enterprise DevOps Platform on AWS EKS
Terraform-automated private EKS platform with VPN-only cluster access, dedicated Jenkins agent node groups, namespace isolation, and IRSA/OIDC workload identity. Monitoring and logging delivered through Prometheus, Grafana, Loki, and Promtail.

### Three-Tier Architecture on AWS ECS Fargate
Production-style deployment path of CloudFront, ALB, ECS Fargate services, and RDS PostgreSQL, provisioned entirely with Terraform. Includes defense-in-depth security group design and remote state with S3 backend locking.

### TechMart Platform
Automated Kubernetes environment combining GitOps, observability, and CI/CD pipelines for hands-on platform engineering practice.

## Professional Experience

**DevOps Engineer — Que Cloud Solutions, Lahore** · Dec 2024 – Jun 2026

- Provisioned development, staging, and production EKS clusters with private API endpoints and VPN-only administration.
- Implemented IRSA and OIDC workload identity for 15+ microservices, replacing node-level IAM with least-privilege service roles.
- Deployed ArgoCD-based GitOps delivery across Kubernetes environments, reducing release time from 35 minutes to 8 minutes (77% improvement).
- Integrated Trivy container scanning and SonarQube static analysis into CI pipelines, identifying 40+ vulnerabilities before deployment.
- Delivered 12 ECS Fargate services behind Application Load Balancer with CloudFront, RDS PostgreSQL, Secrets Manager, and CloudWatch logging.
- Resolved production incidents including CrashLoopBackOff failures and HTTP 503 outages through systematic root-cause analysis.

## Education

University of Education, Lahore

## Contact

Email: [jaffar.devops052@gmail.com](mailto:jaffar.devops052@gmail.com)
Phone: +92 320 9452558
