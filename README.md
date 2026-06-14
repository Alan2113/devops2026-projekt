# DevOps 2026 — Projekt CI/CD na AKS

Aplikacja webowa (Flask) z pipeline CI/CD wdrażana na Azure Kubernetes Service.

## Stack
- Aplikacja: Python / Flask (endpoint `/health`)
- Konteneryzacja: Docker
- CI/CD: GitHub Actions
- Rejestr: Azure Container Registry
- Orkiestracja: Azure Kubernetes Service
- IaC: Terraform (LAB-04+)

## Etapy
- **lab03** — podstawowy pipeline build/test/push, ręczna infra + deploy
- **lab04** — infrastruktura w Terraform + auto-rollout
- **lab05** — GitOps, remote state, OIDC
