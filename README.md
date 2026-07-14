<p align="center">
  <img src="assets/banner.jpg" alt="" width="100%" />
</p>

<h1 align="center">hey, I'm Vandit 👋</h1>

<p align="center">
  Go engineer who builds <b>distributed systems</b> by day and ships <b>indie products</b> by night.<br/>
  I like taking things apart to figure out how they work, then rebuilding them from scratch.<br/>
  (yes, that includes a container runtime and a Docker clone.)
</p>

<p align="center">
  <a href="https://vandit.dev"><img src="https://img.shields.io/badge/vandit.dev-000000?style=flat-square&logo=vercel&logoColor=white" alt="website" /></a>
  <a href="https://www.linkedin.com/in/vandit-singh/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="https://x.com/v4nd1t"><img src="https://img.shields.io/badge/@v4nd1t-000000?style=flat-square&logo=x&logoColor=white" alt="x" /></a>
  <a href="mailto:vanditsinghkv@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email" /></a>
</p>

---

### what I'm up to

- **Day job:** Member of Technical Staff at **FluidCloud**. Building a Go cloud scanner (Terraform coverage across 10+ AWS services), observability that survives production (OpenTelemetry to Prometheus/Grafana), and service-to-service auth with Keycloak.
- **Before that:** hardened container images at **RapidFort** that shipped to the U.S. DoD, and cut CVEs ~80% by profiling what actually runs.
- **Off the clock:** I play guitar and there's a decent chance Spotify is open right now. Proof lives on [vandit.dev](https://vandit.dev).

### the indie arc

Two products I'm bootstrapping solo (closed source, for now):

- 🧵 **[ThreadCite](https://threadcite.live)** finds the Reddit threads ranking on Google for your keywords, tracks your share of voice, and hands you a coached reply for each. Reddit leads, minus the ban risk.
- 👁️ **[Argus](https://argushq.cc)** is a Chrome extension for X that reads your real funnel (reach, visits, follows, saves) and tells you who to reply to, in your own voice. Turns reach into followers, not vanity numbers.

### stuff I've built

- [**phile-storage**](https://github.com/Vandit1604/phile-storage): content-addressed P2P storage in Go (CIDv1, sha2-256) over go-libp2p, with Kademlia DHT routing and a custom block-transfer protocol.
- [**dockerium**](https://github.com/Vandit1604/dockerium) / [**xontainer**](https://github.com/Vandit1604/xontainer): a minimal rootless container runtime on Linux namespaces and the Docker API. (the "from scratch" I warned you about.)
- [**go-lb**](https://github.com/Vandit1604/go-lb): a small HTTP load balancer with round-robin routing and health checks.
- [**otlp-remote-write-poc**](https://github.com/Vandit1604/otlp-remote-write-poc): OpenTelemetry Collector metrics into Prometheus via remote write.
- [**emailguard**](https://github.com/Vandit1604/emailguard): a fast Go package for filtering disposable email domains at signup.

### code I've merged into things you probably use

- **Prometheus:** result limiting on the `/query` and `/query_range` endpoints; exposed `direct_reclaims_total` in `memcached_exporter`.
- **Kubernetes:** a regression test in core `kubernetes/kubernetes`, plus 5+ PRs to `test-infra` improving how Prow runs CI.
- **Jenkins:** rebuilt the docs (11M+ users) on GatsbyJS + Antora, shipped Helm charts and CI/CD to `jenkins-infra`. Was a GSoC '23 mentee, liked it enough to come back as a '24 mentor.

### tech I reach for

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white)

<p align="center"><i>always building something. usually with a guitar nearby.</i></p>
