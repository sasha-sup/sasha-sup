<div align="center">

# Aleksandr Suprun

DevOps / Platform Engineer · Tbilisi, Georgia

7 years building infra that on-call engineers sleep through at night —
bare-metal datacenters, Kubernetes, GPU clusters for ML/LLM,
and the glue that keeps it all reachable.

<a href="https://github.com/sasha-sup"><img src="https://img.shields.io/badge/GitHub-sasha--sup-0f172a?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://linkedin.com/in/aleksandr-suprun"><img src="https://img.shields.io/badge/LinkedIn-aleksandr--suprun-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://sashasup.link"><img src="https://img.shields.io/badge/Website-sashasup.link-1d4ed8?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
<a href="https://sashasup.link/cv?lang=en"><img src="https://img.shields.io/badge/CV-PDF-475569?style=flat-square&logo=readthedocs&logoColor=white" alt="CV"/></a>
<a href="https://t.me/sasha_sup"><img src="https://img.shields.io/badge/Telegram-sasha__sup-26a5e4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="mailto:a.suprun1312@gmail.com"><img src="https://img.shields.io/badge/Email-a.suprun1312%40gmail.com-475569?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

**English** · <a href="./README.ru.md">Русский</a>

</div>

---

## Path

| Years | Where | Role | What I worked on |
| --- | --- | --- | --- |
| 2023 – 2026 | Progressive Mind · Dubai | Senior DevOps | K8s + GPU/ML platform, SSO, custom KMS, multi-DC HA, DR |
| 2023 | Sweatcoin · London | DevOps | Monitoring stack, Ansible / Terraform polish |
| 2021 – 2023 | Appello Software · Sydney | DevOps | −15% AWS spend, +40% CI/CD speed, reusable IaC |
| 2020 – 2021 | RT Labs · Moscow | DevOps | Secure VMware cloud, Ansible / GitLab CI, −70% manual ops |
| 2018 – 2020 | Chestny Znak · Moscow | Linux Engineer | 1200+ servers, 3 datacenters, 24/7 on-call |

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,gitlab,githubactions,jenkins,bash,python,prometheus,grafana,postgres,mysql,mongodb,redis,nginx,linux&perline=10" alt="Tech stack"/>
</p>

**Platform** Talos Linux · Kubespray · kubeadm · EKS · Helm · GitOps
**Observability** VictoriaMetrics · VictoriaLogs · AlertManager · Zabbix · CloudWatch · ELK
**Security** Keycloak (SSO/OIDC) · HashiCorp Vault · custom KMS · LUKS
**HA & Networking** HAProxy · multi-DC · VIP failover
**Data** ClickHouse · Elasticsearch
**AI/ML** GPU scheduling (NVIDIA MIG, time-slicing) · ML pipelines · agent-based systems · RAG

## Things I actually built

- **Custom KMS for LUKS** with heartbeat-based node validation — disks unlock only while the node is healthy and in the cluster.
- **GPU Kubernetes** for ML/LLM workloads on NVIDIA MIG + time-slicing — got real utilization out of expensive cards.
- **Multi-DC HA** with HAProxy and VIP failover, plus an access-control matrix humans can actually read.
- **DR you can trust** — automated backup validation for PostgreSQL, MongoDB, ClickHouse, Elasticsearch. Performed a zero-loss Elasticsearch migration.
- **Centralized SSO** via Keycloak for GitLab, Grafana, Vault, and internal apps — one login, one audit trail.
- **Dynamic K8s staging** spun up per merge request via GitLab CI and Helm.

## Certifications

HashiCorp Terraform Associate · AWS Certified Cloud Practitioner · AWS Knowledge: Architecting · AWS Knowledge: Amazon EKS

## How I work

- **Boring infra wins.** Something a tired on-call engineer can debug at 3am beats something clever.
- **Verify, then verify again.** Live state beats logs, two checks beat one, canary beats faith.
- **Automate the second time.** First time manually — to make sure I understand it. Second time scripted.
- **Observability is part of the design**, not something bolted on after the postmortem.
- **Secure defaults from day one** — identity, secrets, recovery — retrofitting them never goes well.
