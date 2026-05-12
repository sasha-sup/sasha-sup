<div align="center">

# Aleksandr Suprun

DevOps / Platform Engineer · Тбилиси, Грузия

7 лет строю инфраструктуру, через которую дежурный спокойно спит ночью —
bare-metal-ДЦ, Kubernetes, GPU-кластеры для ML/LLM
и тот самый клей, который держит всё вместе и доступным.

<a href="https://github.com/sasha-sup"><img src="https://img.shields.io/badge/GitHub-sasha--sup-0f172a?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://linkedin.com/in/aleksandr-suprun"><img src="https://img.shields.io/badge/LinkedIn-aleksandr--suprun-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://sashasup.link"><img src="https://img.shields.io/badge/Website-sashasup.link-1d4ed8?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
<a href="https://sashasup.link/cv?lang=ru"><img src="https://img.shields.io/badge/Резюме-PDF-475569?style=flat-square&logo=readthedocs&logoColor=white" alt="CV"/></a>
<a href="https://t.me/sasha_sup"><img src="https://img.shields.io/badge/Telegram-sasha__sup-26a5e4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="mailto:a.suprun1312@gmail.com"><img src="https://img.shields.io/badge/Email-a.suprun1312%40gmail.com-475569?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

<a href="./README.md">English</a> · **Русский**

</div>

---

## Путь

| Годы | Где | Роль | Над чем работал |
| --- | --- | --- | --- |
| 2023 – 2026 | Progressive Mind · Дубай | Senior DevOps | K8s + GPU/ML-платформа, SSO, кастомный KMS, multi-DC HA, DR |
| 2023 | Sweatcoin · Лондон | DevOps | Мониторинг-стек, доработка Ansible и Terraform |
| 2021 – 2023 | Appello Software · Сидней | DevOps | −15% расходов AWS, +40% скорости CI/CD, переиспользуемый IaC |
| 2020 – 2021 | RT Labs · Москва | DevOps | Защищённое VMware-облако, Ansible / GitLab CI, −70% ручных операций |
| 2018 – 2020 | Честный Знак · Москва | Linux Engineer | 1200+ серверов, 3 ДЦ, 24/7 on-call |

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

## Что реально построил

- **Кастомный KMS для LUKS** с heartbeat-валидацией нод — диски разблокируются только пока нода жива и в кластере.
- **GPU Kubernetes** для ML/LLM-нагрузок на NVIDIA MIG и time-slicing — выжал реальную утилизацию из дорогих карт.
- **Multi-DC HA** на HAProxy и VIP-failover плюс матрица доступа, которую можно читать без подсказок.
- **DR, которому можно верить** — автоматическая валидация бэкапов PostgreSQL, MongoDB, ClickHouse, Elasticsearch. Перенёс Elasticsearch без потери данных.
- **Централизованный SSO** через Keycloak для GitLab, Grafana, Vault и внутренних сервисов — один логин, один аудит-трейл.
- **Динамический staging в K8s** под каждый MR через GitLab CI и Helm.

## Сертификаты

HashiCorp Terraform Associate · AWS Certified Cloud Practitioner · AWS Knowledge: Architecting · AWS Knowledge: Amazon EKS

## Как я работаю

- **Скучная инфраструктура выигрывает.** То, что уставший дежурный разберёт в 3 ночи, лучше изобретательного.
- **Проверять, а потом ещё раз.** Живое состояние важнее логов, две проверки лучше одной, canary лучше веры.
- **Автоматизировать со второго раза.** Первый раз — руками, чтобы понять. Второй — уже скриптом.
- **Observability — часть дизайна**, а не реакция после постмортема.
- **Secure defaults с первого дня** — identity, secrets, recovery — потом дотягивать всегда криво.
