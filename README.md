<h1 align="center">Anton Patsev - @patsevanton</h1>

<h4 align="center">👨‍💻 DevOps Engineer | ✍️ Writer</h4>

<p align="center">
    <a href="https://t.me/notes_devops_engineer">
        <img alt="Telegram" src="https://img.shields.io/badge/telegram-1a1b27?&logo=telegram&logoColor=white"></a>
    <a href="https://career.habr.com/chemtech">
        <img alt="Habr Career" src="https://img.shields.io/badge/habr%20career-1a1b27?&logo=habr&logoColor=white"></a>
    <img alt="Profile views" src="https://komarev.com/ghpvc/?username=patsevanton&style=plastic&color=1a1b27">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/patsevanton?style=plastic&color=1a1b27">
</p>

Hi, welcome to my profile! 👋

I'm a DevOps engineer from Omsk, Russia. Most of my work is around Yandex Cloud: infrastructure as code with Terraform and Ansible, Kubernetes clusters, GitOps with FluxCD, and observability with VictoriaMetrics, VictoriaLogs and Grafana.

I write about it in my [Telegram channel](https://t.me/notes_devops_engineer) and on [Habr](https://career.habr.com/chemtech).

## My notable projects

### [victoriametrics-alertmanager-grafana-oncall-telegram](https://github.com/patsevanton/victoriametrics-alertmanager-grafana-oncall-telegram)

Alerting pipeline from `vmalert` through Alertmanager and Grafana OnCall to Telegram: the whole path from a metric crossing its threshold to a notification on the phone, wired and checked end to end.

![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-1a1b27?&logo=victoriametrics&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-1a1b27?&logo=grafana&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-1a1b27?&logo=telegram&logoColor=white)

### [sentry-v29-yc-k8s-elastic](https://github.com/patsevanton/sentry-v29-yc-k8s-elastic)

Self-hosted Sentry 29 in Yandex Cloud on Kubernetes: Kafka, ClickHouse and PostgreSQL alongside it, with the resource sizing and tuning that such a stack actually needs.

![Sentry](https://img.shields.io/badge/Sentry-1a1b27?&logo=sentry&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-1a1b27?&logo=apachekafka&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-1a1b27?&logo=clickhouse&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1b27?&logo=postgresql&logoColor=white)
![Yandex Cloud](https://img.shields.io/badge/Yandex%20Cloud-1a1b27?&logo=yandexcloud&logoColor=white)

### [elastic-chaos-monkey-mixed](https://github.com/patsevanton/elastic-chaos-monkey-mixed)

An Elasticsearch cluster under zone failures: what survives, what gets lost, and how shard allocation and quorum behave when whole availability zones go away.

![Elasticsearch](https://img.shields.io/badge/Elasticsearch-1a1b27?&logo=elasticsearch&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)

### [vault-external-secrets-operator](https://github.com/patsevanton/vault-external-secrets-operator)

Kubernetes secrets from Vault with External Secrets Operator and AppRole: workloads read secrets from the cluster API, and no static tokens sit in manifests.

![Vault](https://img.shields.io/badge/Vault-1a1b27?&logo=vault&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)

### [k8s-priority-eviction-autoscaling](https://github.com/patsevanton/k8s-priority-eviction-autoscaling)

Night-time node savings: overprovisioning pods, `PriorityClass` and KEDA keep a warm capacity reserve, so scale-to-zero workloads still have somewhere to start at 3 a.m.

![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)
![KEDA](https://img.shields.io/badge/KEDA-1a1b27)
![Terraform](https://img.shields.io/badge/Terraform-1a1b27?&logo=terraform&logoColor=white)

### [buildkit-vs-kaniko-benchmark](https://github.com/patsevanton/buildkit-vs-kaniko-benchmark)

Build time, CPU and memory of Kaniko, BuildKit and Buildah inside a cluster: measured numbers instead of vendor claims, so the image builder in CI is a deliberate choice.

![Docker](https://img.shields.io/badge/Docker-1a1b27?&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)

### [gateway-api-tcproute-redis](https://github.com/patsevanton/gateway-api-tcproute-redis)

TCP traffic to Redis through one LoadBalancer with Gateway API and SNI routing: a single entry point for many databases instead of a balancer per instance.

![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-1a1b27?&logo=redis&logoColor=white)

### [yacloud-golang-pg-switch-test](https://github.com/patsevanton/yacloud-golang-pg-switch-test)

How a Go application behaves during a PostgreSQL master switchover in Yandex Cloud: which connection errors surface, what retries help and what the client has to handle itself.

![Go](https://img.shields.io/badge/Go-1a1b27?&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1b27?&logo=postgresql&logoColor=white)
![Yandex Cloud](https://img.shields.io/badge/Yandex%20Cloud-1a1b27?&logo=yandexcloud&logoColor=white)

## More things I've built and written about

- [ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) — an Ansible playbook that turns a clean Ubuntu laptop into a DevOps workstation.
- [k8s-redis-valkey-lab](https://github.com/patsevanton/k8s-redis-valkey-lab) — a test bench that compares Redis and Valkey in Kubernetes.
- [fluxcd-operator-and-status-page](https://github.com/patsevanton/fluxcd-operator-and-status-page) — from Flux CLI to Flux Operator with a built-in status page.
- [russian-conferences-articles](https://github.com/patsevanton/russian-conferences-articles) — talks from Russian conferences and meetups turned into written articles.
- [postgresql_overview_postgres_exporter](https://github.com/patsevanton/postgresql_overview_postgres_exporter) — a Grafana dashboard for `postgres_exporter`: the whole PostgreSQL cluster on one screen.
- [kubespray_terraform_yandex_cloud](https://github.com/patsevanton/kubespray_terraform_yandex_cloud) — Kubernetes in Yandex Cloud with Kubespray and Terraform, including inventory from Terraform state.

## Skills

### Things I know best and love

![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1b27?&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1a1b27?&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-1a1b27?&logo=helm&logoColor=white)
![FluxCD](https://img.shields.io/badge/FluxCD-1a1b27?&logo=flux&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-1a1b27?&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-1a1b27?&logo=ansible&logoColor=white)
![Yandex Cloud](https://img.shields.io/badge/Yandex%20Cloud-1a1b27?&logo=yandexcloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1a1b27?&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1a1b27?&logo=gnu-bash&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-1a1b27?&logo=victoriametrics&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-1a1b27?&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-1a1b27?&logo=grafana&logoColor=white)
![VictoriaLogs](https://img.shields.io/badge/VictoriaLogs-1a1b27?&logo=victoriametrics&logoColor=white)
![Git](https://img.shields.io/badge/Git-1a1b27?&logo=git&logoColor=white)

### I have some experience in

![GitLab CI](https://img.shields.io/badge/GitLab%20CI-1a1b27?&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1a1b27?&logo=githubactions&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-1a1b27?&logo=vault&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-1a1b27?&logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1b27?&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-1a1b27?&logo=clickhouse&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-1a1b27?&logo=apachekafka&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-1a1b27?&logo=minio&logoColor=white)
![Python](https://img.shields.io/badge/Python-1a1b27?&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-1a1b27?&logo=go&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-1a1b27?&logo=packer&logoColor=white)

## GitHub statistics

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=patsevanton&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" width="34%"/>
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=patsevanton&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=percentile&custom_title=Stats" width="65%"/>
</p>

## Activity

### 👷 Check out what I'm currently working on

- [terraform-yacloud-modules/terraform-yandex-kubernetes](https://github.com/terraform-yacloud-modules/terraform-yandex-kubernetes) - Terraform module to manage Kubernetes (K8S) resources within the Yandex.Cloud. (today)
- [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) - Плейбук для автоматической настройки Ubuntu-ноутбука под DevOps: от чистого дистрибутива до рабочего окружения.  Resources (today)
- [patsevanton/k8s-redis-valkey-lab](https://github.com/patsevanton/k8s-redis-valkey-lab) - Стенд для сравнения Redis и Valkey в Kubernetes: Helm-чарты и операторы, функциональность, отказоустойчивость, актуальность версий. (today)
- [terraform-yacloud-modules/terraform-yandex-container-registry](https://github.com/terraform-yacloud-modules/terraform-yandex-container-registry) - Terraform module to manage Container Registry resources within the Yandex.Cloud. (1 day ago)
- [terraform-yacloud-modules/terraform-yandex-clickops-notifier](https://github.com/terraform-yacloud-modules/terraform-yandex-clickops-notifier) -  (1 day ago)

### 🔨 My recent Pull Requests

- [feat: add cluster IAM members and multiple pod CIDR ranges](https://github.com/terraform-yacloud-modules/terraform-yandex-kubernetes/pull/141) on [terraform-yacloud-modules/terraform-yandex-kubernetes](https://github.com/terraform-yacloud-modules/terraform-yandex-kubernetes) (today)
- [Add SAML authentication and GiB disk size support](https://github.com/terraform-yacloud-modules/terraform-yandex-mdb-opensearch/pull/98) on [terraform-yacloud-modules/terraform-yandex-mdb-opensearch](https://github.com/terraform-yacloud-modules/terraform-yandex-mdb-opensearch) (today)
- [feat: add backup retention policy support](https://github.com/terraform-yacloud-modules/terraform-yandex-mdb-mysql/pull/79) on [terraform-yacloud-modules/terraform-yandex-mdb-mysql](https://github.com/terraform-yacloud-modules/terraform-yandex-mdb-mysql) (today)
- [Add backup retention period and extended Redis user ACL options](https://github.com/terraform-yacloud-modules/terraform-yandex-redis/pull/86) on [terraform-yacloud-modules/terraform-yandex-redis](https://github.com/terraform-yacloud-modules/terraform-yandex-redis) (today)
- [feat: extend Airflow cluster configuration options](https://github.com/terraform-yacloud-modules/terraform-yandex-airflow/pull/16) on [terraform-yacloud-modules/terraform-yandex-airflow](https://github.com/terraform-yacloud-modules/terraform-yandex-airflow) (today)

### ⭐ Recent Stars

- [SpolzerMod/yamusic-rs](https://github.com/SpolzerMod/yamusic-rs) - Неофициальный клиент Яндекс Музыки на Rust. Интерфейс как у официального приложения - 65 МБ памяти вместо 850. (today)
- [mnemosyne-oss/mnemosyne](https://github.com/mnemosyne-oss/mnemosyne) - Zero-cloud AI memory that works everywhere. SQLite-backed. One pure-Python dependency. (1 day ago)
- [nosarthur/gita](https://github.com/nosarthur/gita) - Manage many git repos with sanity 从容管理多个git库 (1 day ago)
- [BaaRai/ARTEX](https://github.com/BaaRai/ARTEX) - ARTEX - AI autonomous penetration testing system (English translation; upstream: Autumn-27/ARTEX, AGPL-3.0) (2 days ago)
- [sfewer-r7/CVE-2026-123007](https://github.com/sfewer-r7/CVE-2026-123007) - Proof-of-concept (PoC) scripts for CVE-2026-123007, an integer underflow in NGINX HTTP/2. (2 days ago)

### 👯 Check out some of my recent followers

- [searadacunha](https://github.com/searadacunha)
- [boldotter921](https://github.com/boldotter921)
- [notabiguser](https://github.com/notabiguser)
- [soul-abhi](https://github.com/soul-abhi)
- [a4hmad1](https://github.com/a4hmad1)
