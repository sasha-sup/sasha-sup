<div align="center">

# Aleksandr Suprun

**Senior DevOps / Platform Engineer** · 5+ лет · 1200+ серверов · GPU Kubernetes · сертификаты AWS и HashiCorp

<a href="https://github.com/sasha-sup"><img src="https://img.shields.io/badge/GitHub-sasha--sup-0f172a?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://linkedin.com/in/aleksandr-suprun"><img src="https://img.shields.io/badge/LinkedIn-aleksandr--suprun-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://sashasup.link"><img src="https://img.shields.io/badge/Website-sashasup.link-1d4ed8?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
<a href="https://t.me/sasha_sup"><img src="https://img.shields.io/badge/Telegram-sasha__sup-26a5e4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="mailto:a.suprun1312@gmail.com"><img src="https://img.shields.io/badge/Email-a.suprun1312%40gmail.com-475569?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

<a href="./README.md">English</a> · **Русский**

</div>

---

> **Сейчас** — строю GPU-Kubernetes-платформы для ML/LLM-нагрузок.

## Стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,gitlab,githubactions,jenkins,bash,python,prometheus,grafana,postgres,mysql,mongodb,redis,nginx,linux&perline=10" alt="Tech stack"/>
</p>

**Платформа** Talos Linux · Kubespray · kubeadm · EKS · Helm · GitOps
**Observability** VictoriaMetrics · VictoriaLogs · AlertManager · Zabbix · CloudWatch · ELK
**Безопасность** Keycloak (SSO/OIDC) · HashiCorp Vault · custom KMS · LUKS
**HA и сеть** HAProxy · multi-DC · VIP failover
**Данные** ClickHouse · Elasticsearch
**AI/ML** GPU-планирование (NVIDIA MIG, time-slicing) · ML-пайплайны · агентные системы · RAG

## Эффект

- **40%** ускорение CI/CD — кэширование + prebuilt Docker base-образы
- **15%** снижение расходов AWS — right-sizing инстансов + оптимизация тарифов
- **70%** ручных операций устранено — автоматизация на Bash и Python
- **1200+** Linux-серверов в 3 ДЦ, 24/7 on-call с SLA-driven incident response
- **30 нод** Kubernetes (kubeadm, Kubespray, Talos) — миграция с Docker Swarm на K8s с GitOps; GPU-ноды для ML/LLM через NVIDIA MIG и time-slicing
- **Multi-DC HA** — HAProxy + VIP failover, кастомный KMS для LUKS с heartbeat-валидацией нод
- **DRP и SSO** — автоматизированная валидация бэкапов PostgreSQL, MongoDB, ClickHouse, Elasticsearch; централизованный Keycloak SSO для GitLab, Grafana, Vault

## Принципы

- Автоматизация первична — ручная работа только как исключение.
- Observability — часть дизайна, а не реакция после инцидента.
- Скучная инфраструктура выигрывает; простое побеждает изобретательное.
- Secure defaults: identity, secrets, recovery.
- Reliability и delivery speed — ни одно за счёт другого.

