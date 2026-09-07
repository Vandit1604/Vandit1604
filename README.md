<p align="center">
  <img src="assets/banner.jpg" alt="" width="100%" />
</p>

<h1 align="center">Vandit Singh</h1>

<p align="center">
  I build backend and infrastructure in Go: distributed systems, cloud, and observability.<br/>
  195+ merged open-source PRs, including <b>Kubernetes core</b>, <b>Prometheus</b>, <b>VictoriaMetrics</b>, and <b>Lightning Labs</b> (Bitcoin).
</p>

<p align="center">
  <a href="https://vandit.dev"><img src="https://img.shields.io/badge/vandit.dev-000000?style=flat-square&logo=vercel&logoColor=white" alt="website" /></a>
  <a href="https://vandit.dev/resume"><img src="https://img.shields.io/badge/résumé-2b2b2b?style=flat-square&logo=readdotcv&logoColor=white" alt="resume" /></a>
  <a href="https://cal.com/v4nd1t/30min"><img src="https://img.shields.io/badge/book%20a%20call-006BFF?style=flat-square&logo=cal.com&logoColor=white" alt="book a call" /></a>
  <a href="https://www.linkedin.com/in/vandit-singh/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="https://x.com/v4nd1t"><img src="https://img.shields.io/badge/@v4nd1t-000000?style=flat-square&logo=x&logoColor=white" alt="x" /></a>
</p>

---

## Experience

**FluidCloud** · Member of Technical Staff · *Nov 2025 – present*
- Built Terraform scanning into a **Go** cloud scanner. It reads **10,000+ live AWS resources in under 5 seconds** across 10+ services (Glue, Kinesis, SageMaker).
- Built service-to-service auth from scratch with **Keycloak** (OAuth2, OIDC). It secures all internal API traffic.
- Added observability across 5+ services: **OpenTelemetry** into Prometheus and Grafana, with trace-ID logging.
- Built a cost-reporting pipeline on **Oracle Functions + DuckDB** over billing data.

**Aquanode** · Founding Engineer · *Jun 2025 – Oct 2025*
- Built the **Go control plane** for a GPU cloud. A **reconciliation loop** keeps deployments matching live state across 3 providers (DataCrunch, Hyperstack, Nebius) that have unreliable APIs.
- Built a daemon that runs backups and health checks across the fleet, served through the control-plane API.

**RapidFort** · Software Development Engineer · *Jun 2024 – Nov 2025*
- Hardened **12+ open-source images** shipped in the **U.S. DoD IronBank**. Runtime profiling cut CVEs **~80%** and image size **~60%**.
- Built a **sister-CVE detector** (LLM + Exploit-DB) at an **81% hit rate**, and a multi-tenant config manager (RBAC) used by 4 teams.
- Set up the **ELK + Filebeat** logging stack alone for the CVE scrapers.

## Open source · [195+ merged PRs](https://github.com/search?q=author%3AVandit1604+is%3Apr+is%3Amerged&type=pullrequests) since 2022

- **Kubernetes** — merged a regression test into core [`kubernetes/kubernetes`](https://github.com/kubernetes/kubernetes/pull/122625) (#122625); 4 to [`test-infra`](https://github.com/kubernetes/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) (Prow/CI); 4 to [`kueue`](https://github.com/kubernetes-sigs/kueue/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged); 1 to [`gateway-api`](https://github.com/kubernetes-sigs/gateway-api/pull/2705).
- **Prometheus** — added a `limit` option to `/query` and `/query_range` in core [`prometheus`](https://github.com/prometheus/prometheus/pull/15552) (#15552); 6 to [`prombench`](https://github.com/prometheus/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged); a new metric in [`memcached_exporter`](https://github.com/prometheus/memcached_exporter/pull/227).
- **VictoriaMetrics** — 2 in core [`VictoriaMetrics`](https://github.com/VictoriaMetrics/VictoriaMetrics/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged); 2 in [`metricsql`](https://github.com/VictoriaMetrics/metricsql/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged).
- **Bitcoin / Lightning (Go)** — merged in [`lightning-terminal`](https://github.com/lightninglabs/lightning-terminal/pull/1322) (#1322), [`taproot-assets`](https://github.com/lightninglabs/taproot-assets/pull/2267) (#2267), and [`neutrino`](https://github.com/lightninglabs/neutrino/pull/386) (#386).
- **SuperPlane** — open PRs to [`superplanehq/superplane`](https://github.com/superplanehq/superplane/pulls?q=is%3Apr+author%3AVandit1604): shut down cleanly by draining in-flight work on SIGTERM, and bound a provisioner poll.
- **Jenkins** — rebuilt the docs site (GatsbyJS + Antora) for `jenkins-infra`. **GSoC '23 mentee, '24 mentor.**

## Projects

- [**phile-storage**](https://github.com/Vandit1604/phile-storage) — P2P storage in Go where a file's hash is its address (CIDv1, sha2-256). Built on go-libp2p with Kademlia DHT routing and a custom transfer protocol. It re-hashes and verifies every file on fetch, so you never trust the sender.
- [**dockerium**](https://github.com/Vandit1604/dockerium) / [**xontainer**](https://github.com/Vandit1604/xontainer) — a small rootless container runtime on Linux namespaces and the Docker API.
- [**go-lb**](https://github.com/Vandit1604/go-lb) — an HTTP load balancer with round-robin routing and health checks.
- [**otlp-remote-write-poc**](https://github.com/Vandit1604/otlp-remote-write-poc) — sends OpenTelemetry Collector metrics into Prometheus via remote write.
- [**emailguard**](https://github.com/Vandit1604/emailguard) — a fast Go package that blocks disposable email domains at signup.

## Building solo

- [**ThreadCite**](https://threadcite.live) — finds the Reddit threads that rank on Google for your keywords, tracks your share of voice, and drafts a reply for each.
- [**Argus**](https://argushq.cc) — a Chrome extension for X. It reads your real numbers (reach, visits, follows, saves) and tells you who to reply to.

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white" />
</p>

<p align="center"><a href="https://cal.com/v4nd1t/30min"><b>Hiring, or want to build together? Book a call →</b></a></p>
