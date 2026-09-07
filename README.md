<p align="center">
  <img src="assets/banner.jpg" alt="" width="100%" />
</p>

<h1 align="center">hey, I'm Vandit 👋</h1>

<p align="center">
  Go engineer working on <b>distributed systems</b>, <b>cloud infrastructure</b>, and <b>observability</b>.<br/>
  Merged contributor to <b>Kubernetes core</b>, <b>Prometheus</b>, <b>VictoriaMetrics</b>, and <b>Lightning Labs</b> (Bitcoin).
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

**FluidCloud** · Member of Technical Staff *(Nov 2025 to present)*
I write cloud scanners in **Go** that read live resources across **AWS, Oracle Cloud, and Azure**, provision infra with **Terraform**, and I built **service-to-service auth from scratch** with Keycloak (OAuth2 / OIDC). Also shipped an Oracle Cloud cost-reporting pipeline on **Oracle Functions + DuckDB** over CUR data, and run **OpenTelemetry → Prometheus/Grafana** observability across services.

**Aquanode** · Founding Engineer *(Jun 2025 to Oct 2025)*
Built the **Go control plane** for a GPU cloud from scratch: a **reconciliation loop** that converges deployments onto live state across three providers with unreliable APIs, plus a distributed daemon for backups and health checks.

**RapidFort** · Software Development Engineer *(Jun 2024 to Nov 2025)*
- **Community Images:** hardened **12+ OSS container images** (including **IronBank / DoD** images); runtime profiling cut CVEs ~80% and image size ~60%.
- **Scanner:** worked on the core CVE scanner and built an **AI-assisted "sister-CVE" predictor** (Exploit-DB + LLM) plus multi-tenant config management used across prod/dev/staging.

## Open source

**195+ merged PRs since 2022** (the first landed in Jenkins). I like fixing real problems upstream.

- **Kubernetes:** merged a regression test into core [`kubernetes/kubernetes`](https://github.com/kubernetes/kubernetes/pull/122625) (#122625); 4 PRs to [`test-infra`](https://github.com/kubernetes/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) (Prow/CI); 4 to [`kueue`](https://github.com/kubernetes-sigs/kueue/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged); one to [`gateway-api`](https://github.com/kubernetes-sigs/gateway-api/pull/2705).
- **Prometheus:** added a `limit` parameter to `/query` and `/query_range` in core [`prometheus/prometheus`](https://github.com/prometheus/prometheus/pull/15552) (#15552); 6 PRs to [`prombench`](https://github.com/prometheus/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) (their benchmarking bench); a `direct_reclaims_total` metric in [`memcached_exporter`](https://github.com/prometheus/memcached_exporter/pull/227).
- **VictoriaMetrics:** 2 merged in core [`VictoriaMetrics`](https://github.com/VictoriaMetrics/VictoriaMetrics/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) and 2 in [`metricsql`](https://github.com/VictoriaMetrics/metricsql/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) (lexer + implicit-subquery detection).
- **Bitcoin / Lightning (Go):** merged into Lightning Labs' [`lightning-terminal`](https://github.com/lightninglabs/lightning-terminal/pull/1322) (#1322), [`taproot-assets`](https://github.com/lightninglabs/taproot-assets/pull/2267) (#2267), and [`neutrino`](https://github.com/lightninglabs/neutrino/pull/386) (#386).
- **SuperPlane:** open PRs to [`superplanehq/superplane`](https://github.com/superplanehq/superplane/pulls?q=is%3Apr+author%3AVandit1604) — Go control-plane reliability (graceful SIGTERM draining of in-flight work, bounding a provisioner poll).
- **Jenkins:** rebuilt the documentation site on **GatsbyJS + Antora** and shipped to `jenkins-infra`. **GSoC '23 mentee, '24 mentor.**

## Projects

- [**phile-storage**](https://github.com/Vandit1604/phile-storage): content-addressed P2P storage in Go (CIDv1, sha2-256) over go-libp2p, with Kademlia DHT routing, trustless retrieval (re-hash and verify per fetch), and a custom block-transfer protocol.
- [**dockerium**](https://github.com/Vandit1604/dockerium) / [**xontainer**](https://github.com/Vandit1604/xontainer): a minimal rootless container runtime on Linux namespaces and the Docker API.
- [**go-lb**](https://github.com/Vandit1604/go-lb): a small HTTP load balancer with round-robin routing and health checks.
- [**otlp-remote-write-poc**](https://github.com/Vandit1604/otlp-remote-write-poc): OpenTelemetry Collector metrics into Prometheus via remote write.
- [**emailguard**](https://github.com/Vandit1604/emailguard): a fast Go package for filtering disposable email domains at signup.

## Indie

Two products I'm bootstrapping solo (closed source, for now):

- 🧵 **[ThreadCite](https://threadcite.live)** finds the Reddit threads ranking on Google for your keywords, tracks your share of voice, and hands you a coached reply for each. Reddit leads, minus the ban risk.
- 👁️ **[Argus](https://argushq.cc)** is a Chrome extension for X that reads your real funnel (reach, visits, follows, saves) and tells you who to reply to, in your own voice. Turns reach into followers, not vanity numbers.

## About me

I mainly write Go and I'm into distributed systems and web3 infra (hence the Lightning contributions). I care a lot about building products with tasteful interfaces, the kind you enjoy using.

Away from the keyboard I make music: guitar, and beats in FL Studio. There's usually something playing while I build.

---

<p align="center">
  <a href="https://cal.com/v4nd1t/30min"><b>Want to build together, or hire me? Book a call.</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white" />
</p>
