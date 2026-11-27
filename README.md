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

### Articles on Habr

- [Coroot: eBPF-профилирование, логи, трейсы в приложениях в kubernetes](https://habr.com/ru/articles/1087316/) — Sep 2026
- [Алерты по ошибкам и panic из логов приложений в k8s: VictoriaLogs + vmalert + Alertmanager → Telegram](https://habr.com/ru/articles/1083198/) — Sep 2026
- [Kaniko vs BuildKit vs Buildah: замеряем время, CPU и память сборки в кластере](https://habr.com/ru/articles/1079670/) — Sep 2026
- [Экономия на k8s нодах ночью и предварительно подготовленные k8s ноды утром используя overprovisioning поды](https://habr.com/ru/articles/1076538/) — Aug 2026
- [NORA: лёгкий artifact registry для Kubernetes с карантином свежих пакетов и блокировкой CVE](https://habr.com/ru/articles/1074042/) — Aug 2026
- [Radar: Kubernetes UI, которого не хватало](https://habr.com/ru/articles/1073566/) — Aug 2026
- [От Flux CLI к Flux Operator и Status Page](https://habr.com/ru/articles/1030980/) — May 2026
- [OpenCost в Yandex Cloud — расчёт стоимости Kubernetes по ценам Yandex Cloud](https://habr.com/ru/articles/1009678/) — Mar 2026
- [Хаос-инжиниринг Strimzi Kafka: проверка устойчивости к сбоям через Chaos Mesh](https://habr.com/ru/articles/1002846/) — Feb 2026
- [Мониторинг Strimzi Kafka через kube-prometheus-stack](https://habr.com/ru/articles/992494/) — Feb 2026
- [Как маршрутизировать на разные Redis и другие сервисы через один LoadBalancer по SNI TCP routing используя Gateway API](https://habr.com/ru/articles/987652/) — Jan 2026
- [VictoriaLogs в Kubernetes: от установки до практического применения](https://habr.com/ru/articles/985350/) — Jan 2026

[All my articles on Habr →](https://habr.com/ru/users/chemtech/articles/)

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

- [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) - Плейбук для автоматической настройки Ubuntu-ноутбука под DevOps: от чистого дистрибутива до рабочего окружения.  Resources (today)
- [terraform-yacloud-modules/terraform-yandex-iam](https://github.com/terraform-yacloud-modules/terraform-yandex-iam) - Terraform module to manage IAM resources within the Yandex.Cloud. (4 days ago)
- [groundhog2k/helm-charts](https://github.com/groundhog2k/helm-charts) - Helm charts for open source applications - ready to use for deployment on Kubernetes (4 days ago)
- [terraform-yacloud-modules/terraform-yandex-instance-group](https://github.com/terraform-yacloud-modules/terraform-yandex-instance-group) - Terraform module to manage Compute Instance Group resources within the Yandex.Cloud. (5 days ago)
- [terraform-yacloud-modules/terraform-yandex-kms](https://github.com/terraform-yacloud-modules/terraform-yandex-kms) - Terraform module to manage KMS resources within the Yandex.Cloud. (5 days ago)

### 🔨 My recent Pull Requests

- [feat: добавление httpx, dnsx, naabu и dalfox в recon-цепочку](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation/pull/66) on [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) (today)
- [feat: установка CLI cbh из PyPI и правка числа навыков Claude-BugHunter](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation/pull/65) on [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) (today)
- [docs: правило про ripgrep и ast-grep в AGENTS.md](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation/pull/64) on [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) (today)
- [feat: переключение upstream guardrails на polza](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation/pull/63) on [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) (today)
- [feat: добавление asnmap, interview-me и снятие grill-скиллов](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation/pull/62) on [patsevanton/ansible-for-ubuntu-devops-workstation](https://github.com/patsevanton/ansible-for-ubuntu-devops-workstation) (1 day ago)

### ⭐ Recent Stars

- [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) - 🚀 PR Agent: The Original Open-Source PR Reviewer. This project is not the Qodo free tier. (today)
- [miladbeigi/vaultui](https://github.com/miladbeigi/vaultui) - A k9s-inspired terminal UI for HashiCorp Vault — browse secrets, policies, auth methods, PKI, Transit, and Identity engines without leaving your terminal. (today)
- [getsentry/toolkit](https://github.com/getsentry/toolkit) - Agentic tooling for Sentry (1 day ago)
- [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) - Native YouTube client for Windows in Rust, with SponsorBlock, DeArrow and Return YouTube Dislike built in (1 day ago)
- [vektort13/Detect.Expert](https://github.com/vektort13/Detect.Expert) - Detect.Expert — Fingerprint Protection &#43; Forensics &amp; Antidetect (1 day ago)

### 👯 Check out some of my recent followers

- [vadimisakanov](https://github.com/vadimisakanov)
- [notabiguser](https://github.com/notabiguser)
- [soul-abhi](https://github.com/soul-abhi)
- [a4hmad1](https://github.com/a4hmad1)
- [sebcrown](https://github.com/sebcrown)
