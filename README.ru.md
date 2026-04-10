<div align="center">
  <h1>Aleksandr Suprun</h1>
  <p>
    <strong>Senior DevOps / Platform Engineer</strong>
  </p>
  <p>
    5+ лет построения production-инфраструктуры — от парков в 1200+ серверов и bare-metal ДЦ
    до GPU-кластеров Kubernetes и ML/AI платформ.
  </p>
  <p>
    Сертификаты AWS и HashiCorp
  </p>
  <p>
    <a href="./README.md">English</a> · <strong>Русский</strong>
  </p>
</div>

<div align="center">
  <a href="https://github.com/sasha-sup">
    <img src="https://img.shields.io/badge/GitHub-sasha--sup-0f172a?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://linkedin.com/in/aleksandr-suprun">
    <img src="https://img.shields.io/badge/LinkedIn-aleksandr--suprun-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://sashasup.link">
    <img src="https://img.shields.io/badge/Website-sashasup.link-1d4ed8?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/>
  </a>
  <a href="https://t.me/sasha_sup">
    <img src="https://img.shields.io/badge/Telegram-sasha__sup-26a5e4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
  <a href="mailto:a.suprun1312@gmail.com">
    <img src="https://img.shields.io/badge/Email-a.suprun1312%40gmail.com-475569?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>

---

## О профиле

DevOps / Platform Engineer с 5+ годами практического опыта в bare-metal, облачной (AWS, GCP) и гибридной инфраструктуре. Прошёл путь от Linux-операций на масштабе 1200+ серверов в 3 ДЦ через облачную оптимизацию и IaC-автоматизацию к Kubernetes-платформам, ML/GPU-инфраструктуре и SRE-практикам.

## С чем работаю

| Домен | Стек |
| --- | --- |
| Cloud & Compute | `AWS`, `GCP`, `Linux (RHEL, Ubuntu, Debian, AlmaLinux, Arch)`, `VMware`, `KVM`, `Proxmox`, `bare metal` |
| Containers & Platform | `Kubernetes`, `kubeadm`, `Kubespray`, `Talos Linux`, `EKS`, `Docker`, `Helm`, `GitOps` |
| Delivery & IaC | `Terraform`, `Ansible`, `Ansible Vault`, `GitLab CI`, `GitHub Actions`, `Jenkins`, `Bash`, `Python` |
| Observability | `Prometheus`, `Grafana`, `VictoriaMetrics`, `VictoriaLogs`, `AlertManager`, `CloudWatch`, `Zabbix`, `ELK` |
| Networking & HA | `HAProxy`, `nginx`, `multi-DC`, `VIP failover` |
| Security & Auth | `Keycloak (SSO/OIDC)`, `HashiCorp Vault`, `custom KMS`, `LUKS encryption` |
| Databases | `PostgreSQL`, `MySQL`, `MongoDB`, `Redis`, `ClickHouse`, `Elasticsearch` |
| AI/ML Infra | `GPU scheduling (MIG, time-slicing)`, `ML pipelines`, `agent-based systems`, `RAG` |

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,gitlab,githubactions,jenkins,bash,python,prometheus,grafana,postgres,mysql,mongodb,redis,nginx,linux&perline=10" alt="Tech stack icons"/>
</div>

## Что строю

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Kubernetes и платформы</strong><br/>
      Kubernetes-кластеры (kubeadm, Kubespray, Talos Linux) до 30 нод. Миграция с Docker Swarm на Kubernetes с GitOps. Динамические staging-окружения через Helm и CI/CD. Стандартизация инфраструктуры из 25+ ВМ через Ansible.
    </td>
    <td width="50%" valign="top">
      <strong>ML/GPU и CI/CD</strong><br/>
      GPU-ноды в Kubernetes с NVIDIA MIG и time-slicing для ML/LLM-нагрузок. Архитектура GitLab CI/CD с шаблонами и base-образами. Ускорение ML-пайплайнов. Сокращение времени сборок на 40% через стратегии кэширования.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>SRE и observability</strong><br/>
      Стратегии Disaster Recovery с определёнными RTO/RPO. Автоматизация бэкапов и валидации для PostgreSQL, MongoDB, ClickHouse, Elasticsearch. SRE-дашборды с SLI/SLO-метриками. Стеки мониторинга: Prometheus, Grafana, VictoriaMetrics, Zabbix, AlertManager.
    </td>
    <td width="50%" valign="top">
      <strong>Security и HA</strong><br/>
      Кастомный KMS-сервер для LUKS-шифрования с heartbeat-валидацией нод. Централизованный SSO через Keycloak (GitLab, Grafana, Vault, внутренние сервисы). Multi-DC HA-архитектура с HAProxy и VIP-failover.
    </td>
  </tr>
</table>

## Ключевой эффект

- Построил Kubernetes-кластеры (kubeadm, Kubespray, Talos Linux) до 30 нод; мигрировал нагрузки с Docker Swarm с внедрением GitOps
- Настроил GPU-кластер Kubernetes для ML/LLM-нагрузок с NVIDIA MIG и time-slicing; оптимизировал распределение ресурсов и probes
- Построил кастомный KMS-сервер для LUKS-шифрования дисков с heartbeat-валидацией нод
- Спроектировал multi-DC HA-архитектуру с HAProxy и VIP-failover; разработал матрицу доступа
- Разработал DRP и автоматизировал валидацию бэкапов для PostgreSQL, MongoDB, ClickHouse, Elasticsearch; выполнил миграцию Elasticsearch без потери данных
- Внедрил централизованный SSO через Keycloak с интеграцией в GitLab, Grafana, Vault и внутренние сервисы
- Развернул VictoriaMetrics stack, AlertManager и Zabbix; построил SRE-дашборды с SLI/SLO-метриками
- Сократил расходы на AWS на `15%` через right-sizing инстансов и оптимизацию тарифов
- Ускорил CI/CD-пайплайны на `40%` за счёт кэширования и prebuilt Docker-образов
- Устранил `70%` ручных операций через автоматизацию на Bash и Python
- Обслуживал `1200+` Linux-серверов в `3` ДЦ в режиме 24/7 on-call с SLA-driven incident response

## Инженерные принципы

- Автоматизировать всё повторяемое, пока ручная работа не останется только исключением.
- Считать observability частью дизайна, а не реакцией после инцидента.
- Предпочитать простые и проверяемые платформенные паттерны инфраструктурной изобретательности ради неё самой.
- Закладывать secure defaults с самого начала: identity, secrets, access boundaries, recovery discipline.
- Балансировать reliability и delivery speed, не жертвуя одним ради другого.

## Контакты

<div align="center">
  <a href="https://github.com/sasha-sup">GitHub</a>
  ·
  <a href="https://linkedin.com/in/aleksandr-suprun">LinkedIn</a>
  ·
  <a href="https://sashasup.link">Website</a>
  ·
  <a href="https://t.me/sasha_sup">Telegram</a>
  ·
  <a href="mailto:a.suprun1312@gmail.com">Email</a>
</div>
