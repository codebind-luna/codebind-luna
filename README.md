# 👋 Hi, I'm Luna

### Senior / Staff Backend & Platform Engineer | SRE | Golang | Distributed Systems | Kubernetes

**Open to Staff / Senior Platform Engineering / SRE roles** · Bangalore · Hyderabad · Pune · Remote

I'm a **Senior Software Engineer with 10+ years of experience** building backend services, distributed systems, and the Kubernetes platforms other teams deploy on. My recent work is multi-cluster platform engineering at fleet scale — control-plane design, GitOps architecture, and deployment workflows operating across **500+ Kubernetes clusters**.

I enjoy solving complex engineering problems around **scalability, reliability, concurrency, infrastructure automation, and distributed systems**, in Go and Kubernetes.

---

## 📊 Selected Impact

- **500+ Kubernetes clusters · 60+ applications migrated with zero downtime** — designed the GitOps architecture and platform workflows operating across hundreds of workload clusters, migrating 60+ applications onto it without a single service interruption.
- **Multi-cluster control plane** — designed systems for securely onboarding and managing remote Kubernetes clusters at scale.
- **90% reduction in deployment wait time** — designed parallel, non-blocking deployment strategies in place of serialized rollouts.

---

## 🚀 Featured Projects

**[Ordered Upgrade Operator](https://github.com/codebind-luna/ordered-upgrade-operator)**
- A Kubernetes operator that enforces dependency-aware rollout ordering, upgrading a callee service before its caller so in-flight requests don't fail mid-rollout. Written in Go with a `v1alpha1` CRD, envtest unit coverage and Kind-based end-to-end tests exercising mid-rollout termination.

**[OTel Trace Propagation](https://github.com/codebind-luna/otel-trace-propagation)**
- Distributed tracing where it usually breaks: across a message queue. An HTTP request, a RabbitMQ publish and a worker in a separate process land in a **single trace of five spans**, by carrying W3C trace context on message metadata through a custom OpenTelemetry `TextMapCarrier`. Go, OTel, RabbitMQ, MongoDB and Jaeger, with a compose stack and a CI job that drives a real request and fails unless the trace spans both services.

**[Train Ticket Booking](https://github.com/codebind-luna/train-ticket-booking)**
- A gRPC ticket-booking service in Go built around one invariant: never sell the same seat twice. Seat allocation is a read-then-write, so it is enforced by a single write lock spanning the whole decision and proven by concurrency specs — 200 buyers contending for 20 seats, and 50 simultaneous retries by one buyer — running under the race detector in CI. Ports-and-adapters layering, protobuf/buf codegen, golangci-lint clean.

---

## 🌍 Open Source Contributions

I contribute to open-source infrastructure and cloud-native projects, with a focus on backend systems, Kubernetes, platform engineering and infrastructure automation.

**Airship**
[View Commits](https://github.com/airshipit/deckhand/commits?author=codebind-luna)
- Contributed to the Airship Deckhand configuration management platform by enhancing the secret substitution engine to support one-to-many configuration propagation and designing a development-mode authentication framework that removed Keystone dependencies from local development workflows.

**Openstack-helm-infra**
[View Commits](https://github.com/openstack/openstack-helm-infra/commits?author=codebind-luna)
- Extended the OpenStack-Helm ecosystem by contributing new infrastructure components, Kubernetes controller integrations, and automated integration tests, strengthening deployment automation and release quality.

**Neutron-tempest-plugin**
[View Commits](https://github.com/openstack/neutron-tempest-plugin/commits/master/)
- Expanded OpenStack Neutron's integration test coverage, improving release quality.

---

## 🛠️ Technologies

**Languages**
`Go` `Python` `Bash` `SQL`

**Cloud & Infrastructure**
`AWS` `Terraform` `Ansible` `Docker` `Kubernetes` `Linux`

**Kubernetes Ecosystem**
`Kubebuilder` `Operator SDK` `Cluster API` `Helm` `Argo CD` `Rancher` `CRDs & Controllers`

**Reliability Engineering**
`SLIs & SLOs` `Error Budgets` `Incident Response` `Postmortems` `Capacity Planning` `Progressive Delivery`

**Observability**
`Prometheus` `Grafana` `OpenTelemetry` `Loki` `Alertmanager` `Thanos`

**CI/CD & Delivery**
`GitHub Actions` `Argo Workflows` `Zuul` `GitOps`

**Data & Messaging**
`Kafka` `RabbitMQ` `PostgreSQL` `MongoDB` `Redis` `gRPC`

---

## 🌱 Currently Exploring

- AI/LLM infrastructure — GPU scheduling, vLLM and inference platforms on Kubernetes
- MLOps & Kubernetes-native ML infrastructure
- Multi-cluster fleet management and internal platform APIs
- eBPF and Cilium for network-level observability
- SLO-driven reliability at scale — Thanos, long-retention metrics, alert quality
- Infrastructure cost efficiency and capacity modelling

---

## 🤝 Let's Connect

I'm interested in conversations around:

Backend Engineering · Platform Engineering · Kubernetes · Distributed Systems · Cloud Infrastructure · Observability · AI Infrastructure

[LinkedIn](https://www.linkedin.com/in/luna-das-2610a099/) · [Email](mailto:cse2013luna@gmail.com)
