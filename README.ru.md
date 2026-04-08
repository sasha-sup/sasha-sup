<div align="center">
  <h1>Aleksandr Suprun</h1>
  <p>
    <strong>Senior DevOps • Platform • Infrastructure Engineer</strong>
  </p>
  <p>
    5+ лет проектирования и эксплуатации production-платформ в cloud (AWS, GCP) и bare-metal средах
    с фокусом на Kubernetes, автоматизацию, надёжность и безопасную поставку.
  </p>
  <p>
    Сертифицирован по AWS и HashiCorp • Тбилиси, Грузия
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

DevOps-инженер с 5+ годами опыта управления cloud и bare-metal инфраструктурой. Автоматизирую деплойменты и провижининг окружений с помощью Terraform, Ansible, Kubernetes (EKS и vanilla) и CI/CD pipelines.

Моя зона работы: platform engineering, infrastructure as code, observability и security в AWS, GCP и on-prem средах — превращаю операционную сложность в повторяемые системы с более надёжной поставкой, восстановлением и сигналом из production.

## С чем работаю

| Домен | Стек |
| --- | --- |
| Cloud & Compute | `AWS`, `GCP`, `Linux (RHEL, Ubuntu, Debian, Alma)`, `VMware`, `KVM`, `Proxmox`, `bare metal` |
| Containers & Platform | `Kubernetes`, `EKS`, `kubeadm`, `Kubespray`, `Docker`, `Helm`, `GitOps` |
| Delivery & IaC | `Terraform`, `Ansible`, `Ansible Vault`, `GitLab CI`, `GitHub Actions`, `Jenkins`, `Bash`, `Python` |
| Observability & Data | `Prometheus`, `Grafana`, `VictoriaMetrics`, `Alertmanager`, `CloudWatch`, `Zabbix`, `ELK`, `PostgreSQL`, `MySQL`, `MongoDB`, `Redis`, `ClickHouse` |
| Edge & Access | `nginx`, `HAProxy`, `Keycloak`, `Consul` |

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,gitlab,githubactions,jenkins,bash,python,prometheus,grafana,postgres,mysql,mongodb,redis,nginx,linux&perline=10" alt="Tech stack icons"/>
</div>

## Что строю

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Platform Foundations</strong><br/>
      Kubernetes-кластеры (EKS, kubeadm, Kubespray) с GitOps-подходом и GPU-нодами для ML/LLM workloads. Поставка в несколько окружений через переиспользуемые Helm-чарты и Terraform-модули.
    </td>
    <td width="50%" valign="top">
      <strong>Delivery Systems</strong><br/>
      GitLab CI/CD pipelines с шаблонами и base images, динамические staging-окружения per PR в Kubernetes, кэширование пакетов — сокращение времени pipeline на 40%.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Reliability & Recovery</strong><br/>
      Стеки мониторинга на VictoriaMetrics, Prometheus, Grafana и Zabbix. Автоматизированные бэкапы PostgreSQL, MongoDB, ClickHouse и Elasticsearch с проверенными планами disaster recovery.
    </td>
    <td width="50%" valign="top">
      <strong>Secure Operations</strong><br/>
      Централизованный SSO через Keycloak (Grafana, Kubernetes, GitLab), Ansible Vault для управления секретами, усиленные operational workflows с контролируемыми границами доступа.
    </td>
  </tr>
</table>

## Ключевой эффект

- Построил GPU-enabled Kubernetes кластер для ML/LLM workloads с MIG и time-slicing, оптимизировал утилизацию ресурсов и probes. *(Progressive Mind)*
- Спроектировал DRP и автоматизировал бэкапы PostgreSQL, MongoDB, ClickHouse и Elasticsearch; выполнил zero-loss миграцию Elasticsearch. *(Progressive Mind)*
- Перевёл workloads с Docker Swarm на Kubernetes (Kubespray, kubeadm) и выстроил GitOps-driven delivery patterns. *(Progressive Mind)*
- Внедрил централизованный SSO через Keycloak для Grafana, Kubernetes и GitLab. *(Progressive Mind)*
- Реализовал динамические staging-окружения в Kubernetes через GitLab CI и Helm. *(Progressive Mind)*
- Снизил AWS-затраты на `15%` за счёт right-sizing инстансов и оптимизации планов. *(Appello Software)*
- Ускорил CI/CD pipelines на `40%` через кэширование пакетов и prebuilt Docker images. *(Appello Software)*
- Убрал `70%` повторяющейся операционной работы через автоматизацию на Bash и Python. *(RT Labs)*
- Поддерживал `1200+` Linux-серверов в `3` data centers в режиме 24/7 on-call с SLA-driven incident response. *(Chestny Znak)*

## Инженерные принципы

- Автоматизировать всё повторяемое, пока ручная работа не остаётся только исключением.
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
