### Hi, I'm Vandit

Go engineer working on distributed systems, storage, and p2p (libp2p). Member of Technical Staff at FluidCloud. Merged contributor to Kubernetes, Prometheus, and Jenkins.

- **Now:** at FluidCloud, building a Go cloud scanner (Terraform coverage across 10+ AWS services), observability across microservices (OpenTelemetry to Prometheus/Grafana), and service-to-service auth with Keycloak.
- **Before:** at RapidFort, authored 12+ hardened, minimal OSS images (shipped IronBank images used by the U.S. DoD; runtime profiling cut CVEs ~80% and image size ~60%), and built security tooling around CVE detection.
- **Writing** at [vandit.dev](https://vandit.dev).

#### Selected work
- [**phile-storage**](https://github.com/Vandit1604/phile-storage): content-addressed P2P storage in Go (CIDv1, sha2-256) over go-libp2p, with Kademlia DHT routing and a custom block-transfer stream protocol.
- [**dockerium**](https://github.com/Vandit1604/dockerium) / [**xontainer**](https://github.com/Vandit1604/xontainer): a minimal rootless container runtime on Linux namespaces and the Docker API.
- [**go-lb**](https://github.com/Vandit1604/go-lb): a small HTTP load balancer with round-robin routing and passive health checks.
- [**otlp-remote-write-poc**](https://github.com/Vandit1604/otlp-remote-write-poc): OpenTelemetry Collector metrics into Prometheus via remote write.
- [**emailguard**](https://github.com/Vandit1604/emailguard): a fast Go package for filtering disposable email domains at signup.

#### Open source
- **Prometheus:** added query-result limiting to `/query` and `/query_range`; exposed `direct_reclaims_total` in `memcached_exporter`.
- **Kubernetes:** merged a regression test into `kubernetes/kubernetes`; 5+ PRs to `test-infra` improving Prow job orchestration.
- **Jenkins (GSoC '23):** migrated the docs (11M+ users) to a versioned GatsbyJS + Antora architecture; Helm charts and CI/CD for `jenkins-infra`.

#### Reach me
[vandit.dev](https://vandit.dev) · [LinkedIn](https://www.linkedin.com/in/vandit-singh/) · [X](https://x.com/v4nd1t) · vanditsinghkv@gmail.com
