<h1 align="center">Hi, I'm Aryn 👋</h1>

<p align="center">
  <b>Software Engineer · Backend, DevOps &amp; AI Infrastructure</b> · Astana, Kazakhstan 🇰🇿<br/>
  On-prem Kubernetes and GPU platforms, production backends, Telegram tooling.
</p>

<p align="center">
  <a href="mailto:aryn@sek.su"><img alt="Email" src="https://img.shields.io/badge/aryn%40sek.su-mail-informational?style=flat-square&logo=protonmail&logoColor=white"></a>
  <a href="https://t.me/arynyklas"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@arynyklas-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
  <a href="https://t.me/aryn_dev"><img alt="Channel" src="https://img.shields.io/badge/channel-@aryn__dev-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/arynyklas/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-arynyklas-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=arynyklas&style=flat-square&color=blueviolet">
  <a href="https://github.com/arynyklas?tab=followers"><img alt="Followers" src="https://img.shields.io/github/followers/arynyklas?style=flat-square&label=Followers&logo=github&color=181717"></a>
</p>

---

### About

- 🛠 **Fullstack Software Engineer** at the **Financial Monitoring Agency of Kazakhstan**. One of two engineers running its on-prem platform: Proxmox VE, Kubernetes (Talos, k3s) with GitOps, SSO, secrets, networking and monitoring.
- 🧠 Operate a multi-node **H200 GPU** cluster that serves LLMs on vLLM behind an OpenAI-compatible gateway (+32% Gemma-4-31B throughput per GPU from bf16 and speculative decoding); building our own inference engine in Rust and C++/CUDA to run alongside it.
- 🐍 Build data pipelines on top of it: procurement-risk analytics and media monitoring with millions of records on PostgreSQL, ClickHouse and S3, classified by LLMs on our own GPUs.
- 🧪 Pragmatic about **DDD, dependency injection, integration tests on ephemeral Postgres**, and CI/CD that doesn't lie.
- 🦀 Reach for **Rust** when Python is the wrong tool: proxies, e-signature middleware, data migration and reconciliation.
- 🎓 BCS @ **Astana IT University** · maintainer of **ReMoodle**, a deadline notifier for students.

---

### 💻 My stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,js,rust,go,c,cpp,bash,react,tailwind,vite,bun,fastapi,nodejs,graphql,postgres,mysql,sqlite,redis,mongodb,elasticsearch,rabbitmq,docker,kubernetes,terraform,ansible,aws,ipfs,nginx,grafana,prometheus,pytorch,linux,git,github,gitlab,githubactions,sentry,cloudflare,vscode&perline=10" alt="skills"/>
  </a>
</p>

#### Languages

`Python` · `TypeScript` / `JavaScript` · `Rust` · `Go` · `C` / `C++` · `SQL` · `Bash` · `HTML` / `CSS`

#### Infrastructure

**Virtualization:** Proxmox VE · iSCSI and FC SAN storage · multipath · LVM · OCFS2 · ZFS · Proxmox Backup Server

**Kubernetes & GitOps:** Talos · k3s · Cilium (Gateway API) · Helm · Kustomize · Flux · ArgoCD · cert-manager · CloudNativePG

**Containers & IaC:** Docker · Docker Compose · podman · Terraform / OpenTofu · Ansible · cloud-init · AWS · Cloudflare · IPFS

**Network:** OPNsense · HAProxy · Traefik · Nginx · Caddy · Envoy · WireGuard · IPsec (strongSwan) · custom mesh VPN · nftables · PowerDNS (DNSSEC)

**Identity & secrets:** Keycloak (OIDC, SCIM) · oauth2-proxy · OpenBao / Vault · internal PKI · SOPS / age

#### AI infrastructure

vLLM (speculative decoding, FP8 / NVFP4, 1M-token context) · llama.cpp · Envoy AI Gateway · Gateway API Inference Extension · NVIDIA GPU Operator · MIG · DCGM · PyTorch

#### CI/CD & Observability

GitHub Actions (test → build → deploy) · GitLab CI · werf · kubeconform · gitleaks · pre-commit

Grafana · Prometheus · Alertmanager · Loki · Tempo · VictoriaMetrics · Sentry · OpenTelemetry

#### Backend (Python)

**Web:** FastAPI · Litestar · Granian · aiohttp · Starlette

**Telegram:** Telethon · aiogram 3 · aiogram_dialog · Pyrogram / pyrofork · pytdlib · TON Connect

**Async / messaging:** asyncio · arq · FastStream · Celery · Dagster · gRPC

**Data layer:** SQLAlchemy · Alembic · asyncpg · Pydantic · dishka · beanie · attrs · msgspec

**HTTP / scraping:** httpx · niquests · aiohttp · Selenium · Playwright · BeautifulSoup

**LLM / AI:** self-hosted vLLM · Ollama · OpenAI · Anthropic · LiteLLM · LangChain (where it earns its keep)

#### Frontend

React · Mantine · TanStack Query / Router · zod · Vite · Tailwind CSS · TypeScript · Bun

#### Systems / Rust

Tokio · axum · Serde · SQLx · Reqwest · clap · grammers (MTProto): proxies, e-signature middleware, migration and reconciliation tools

#### Databases

PostgreSQL (Patroni, replicas, FDW, pgvector, PgBouncer) · ClickHouse · Redis / Valkey · MongoDB · ElasticSearch · Qdrant · Neo4j · StarRocks · MySQL · SQLite

#### Messaging & Storage

NATS / JetStream · RabbitMQ · Kafka · SeaweedFS · MinIO · S3-compatible

#### Tooling

Linux · Bash · Make · just · Poetry · uv · ruff · ty · mypy · pytest · Cargo · pnpm · Git · GitHub · GitLab · VS Code

---

### 🚀 Featured projects

| Repo | Stack | What it does |
|------|-------|--------------|
| [**tgin**](https://github.com/arynyklas/tgin) | Rust | Ingress and load balancer for high-load Telegram bots (my maintained fork). About 0.1 ms proxy overhead, up to 9.9k rps; the 1.0 LTS rewrite adds MTProto accounts. |
| [**open-ncalayer**](https://github.com/arynyklas/open-ncalayer) | Rust | Open-source, cross-platform replacement for NCALayer, Kazakhstan's e-signature browser middleware. |
| [**oh-my-pi**](https://github.com/arynyklas/oh-my-pi) | TypeScript · Bun | AI coding agent fork with a multi-tenant LLM auth gateway: ACLs, credential pools, audit. |
| [**tg_gifts_notifier**](https://github.com/arynyklas/tg_gifts_notifier) ⭐ 52 | Python · Telethon | Live notifier for new Telegram Gifts, runs [@gifts_detector](https://t.me/gifts_detector). |
| [**SPOwnerBot**](https://github.com/arynyklas/SPOwnerBot) ⭐ 24 | Python · Telethon | Finds the owner of a sticker pack; about 40k users. |
| [**ArynIDBot**](https://github.com/arynyklas/ArynIDBot) ⭐ 12 | Python · Telethon | Telegram ID and media metadata inspector. |
| [**tma-template**](https://github.com/arynyklas/tma-template) | Python | Production-ready backend template for Telegram Mini Apps and bots. |

---

### 🌐 Spoken languages

🇷🇺 Russian · 🇰🇿 Kazakh — native &nbsp;|&nbsp; 🇬🇧 English — highly proficient &nbsp;|&nbsp; 🇨🇿 Czech — B1 &nbsp;|&nbsp; 🇫🇷 French — A1

---

### 📊 GitHub stats

<p align="center">
  <img alt="GitHub stats" src="https://github-readme-stats-eight-theta.vercel.app/api?username=arynyklas&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" height="170">
  <img alt="Streak" src="https://streak-stats.demolab.com?user=arynyklas&theme=github-dark&hide_border=true" height="170">
</p>

<p align="center">
  <img alt="Top languages" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=arynyklas&layout=compact&theme=github_dark&hide_border=true&langs_count=12&card_width=480">
</p>

### 📈 Contribution graph

<p align="center">
  <img alt="Activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=arynyklas&theme=github-compact&hide_border=true&area=true">
</p>

---

<p align="center"><sub>Open to infrastructure, SRE and backend work — <a href="mailto:aryn@sek.su">aryn@sek.su</a></sub></p>
<p align="center"><sub>⭐ From <a href="https://github.com/arynyklas">arynyklas</a> · brewed with ☕ in Astana</sub></p>
