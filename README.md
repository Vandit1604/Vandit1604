# Vandit Singh

Go backend & infrastructure engineer: distributed systems, cloud, observability. 195+ merged open-source PRs, including Kubernetes core, Prometheus, VictoriaMetrics, and Lightning Labs (Bitcoin).

[vandit.dev](https://vandit.dev) · [résumé](https://vandit.dev/resume) · [book a call](https://cal.com/v4nd1t/30min) · [LinkedIn](https://www.linkedin.com/in/vandit-singh/) · [X](https://x.com/v4nd1t)

## Experience

**FluidCloud** — Member of Technical Staff · Nov 2025–present
Go cloud scanner reading 10,000+ live AWS resources in under 5s. Service-to-service auth from scratch (Keycloak, OAuth2/OIDC). OpenTelemetry into Prometheus/Grafana. Cost pipeline on Oracle Functions + DuckDB.

**Aquanode** — Founding Engineer · Jun–Oct 2025
Built the Go control plane for a GPU cloud: a reconciliation loop that matches live state across 3 providers with unreliable APIs, plus a fleet backup/health daemon.

**RapidFort** — Software Development Engineer · Jun 2024–Nov 2025
12+ hardened images shipped in the U.S. DoD IronBank (CVEs ~80% down, size ~60% down). Sister-CVE detector (LLM + Exploit-DB) at an 81% hit rate. Set up the ELK stack.

## Open source · [195+ merged PRs](https://github.com/search?q=author%3AVandit1604+is%3Apr+is%3Amerged&type=pullrequests) since 2022

- Kubernetes — core [#122625](https://github.com/kubernetes/kubernetes/pull/122625); [test-infra](https://github.com/kubernetes/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) ×4; [kueue](https://github.com/kubernetes-sigs/kueue/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) ×4; [gateway-api](https://github.com/kubernetes-sigs/gateway-api/pull/2705).
- Prometheus — `limit` param in core [#15552](https://github.com/prometheus/prometheus/pull/15552); [prombench](https://github.com/prometheus/test-infra/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) ×6; [memcached_exporter](https://github.com/prometheus/memcached_exporter/pull/227).
- VictoriaMetrics — [core](https://github.com/VictoriaMetrics/VictoriaMetrics/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) ×2; [metricsql](https://github.com/VictoriaMetrics/metricsql/pulls?q=is%3Apr+author%3AVandit1604+is%3Amerged) ×2.
- Lightning (Go) — [lightning-terminal](https://github.com/lightninglabs/lightning-terminal/pull/1322) #1322, [taproot-assets](https://github.com/lightninglabs/taproot-assets/pull/2267) #2267, [neutrino](https://github.com/lightninglabs/neutrino/pull/386) #386.
- SuperPlane — [open PRs](https://github.com/superplanehq/superplane/pulls?q=is%3Apr+author%3AVandit1604): SIGTERM drain, poll bounding.
- Jenkins — docs rebuild (Gatsby + Antora). GSoC '23 mentee, '24 mentor.

## Projects

- [phile-storage](https://github.com/Vandit1604/phile-storage) — P2P storage in Go, a file's hash is its address (CIDv1, go-libp2p, Kademlia DHT, trustless retrieval).
- [dockerium](https://github.com/Vandit1604/dockerium) / [xontainer](https://github.com/Vandit1604/xontainer) — rootless container runtime on Linux namespaces.
- [go-lb](https://github.com/Vandit1604/go-lb) — HTTP load balancer with round-robin and health checks.
- [otlp-remote-write-poc](https://github.com/Vandit1604/otlp-remote-write-poc) — OpenTelemetry metrics into Prometheus via remote write.
- [emailguard](https://github.com/Vandit1604/emailguard) — Go package that blocks disposable email domains.

## Building solo

- [ThreadCite](https://threadcite.live) — finds Reddit threads ranking on Google for your keywords and drafts a reply for each.
- [Argus](https://argushq.cc) — Chrome extension for X that reads your real funnel and tells you who to reply to.

Stack: Go, Kubernetes, Prometheus, OpenTelemetry, Terraform, Docker, PostgreSQL, Linux.
