<div align="center">

# Nur Yanfa

**Backend Engineer (Go) · DevOps · Security-minded**

Informatics student in Bandung, Indonesia. I build backend systems in Go that are observable, tested, and honest about their limits.

**Open to:** junior backend / DevOps / security roles and internships · remote or Bandung/Jakarta

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://www.nuryanfa.my.id)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhamad-nur-yanfa-069036368/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nuryanfa@gmail.com)

</div>

---

## Featured projects

### [AegisGate](https://github.com/Nuryanfa/AegisGate) · Go API gateway with a gRPC control plane
API gateway that enforces request-security policies and pushes validated routing config to multiple gateway instances.
- HTTP data path on `net/http`; config distributed over bidirectional gRPC streaming with ACK/NACK and atomic runtime swaps
- API-key auth, Redis Lua token-bucket rate limiting, audit/enforce WAF inspection
- Prometheus metrics, OpenTelemetry tracing, CI with race tests and fuzz smoke tests, [documented benchmarks](https://github.com/Nuryanfa/AegisGate/blob/main/docs/benchmarks/v0.8-control-plane.md), ADRs

`Go` `gRPC` `Protobuf` `Redis` `Prometheus` `OpenTelemetry` `Docker`

### [TaskForge](https://github.com/Nuryanfa/TaskForge) · Durable background job platform
PostgreSQL-backed job queue with leased execution, retries, dead-letter queue, cron scheduling, and workflow DAGs with saga compensation.
- Transactional outbox publishing job events to NATS JetStream
- End-to-end tracing from HTTP request to every worker attempt
- SLOs with burn-rate alerts and a Grafana dashboard; `make demo` walks through an incident

`Go` `PostgreSQL` `NATS JetStream` `Prometheus` `Grafana` `Jaeger`

### [Inkproof](https://github.com/Nuryanfa/Inkproof) · PDF digital signature verifier *(in progress)*
Checks whether a signed PDF was signed by a trusted certificate and whether it was modified after signing.
- X.509 chain validation, OCSP/CRL revocation, RFC 3161 timestamps
- Threat model, fuzzed parser, SSRF-guarded network egress
- Go library, CLI, and REST API

`Go` `PKI` `X.509` `Application Security`

### [SecureNet Enterprise Lab](https://github.com/Nuryanfa/securenet-enterprise-lab) · Purple-team network lab *(in progress)*
Virtualized enterprise network built in versioned releases. v1.0 (MikroTik CHR routing, firewall, NAT, QoS, monitoring, backup) is complete; segmentation, Wazuh SIEM, and ATT&CK-mapped attack simulation are next.

`MikroTik` `Network Security` `Wazuh` `MITRE ATT&CK`

---

## Experience

**DevOps Intern** · <!-- TODO: nama perusahaan/instansi --> · 2026 – present
Deploying a web application to a VPS and building its CI/CD pipeline on GitLab.

---

## Tech stack

**Core:** Go · PostgreSQL · Redis · Docker · Linux · Git
**Distributed & observability:** gRPC · NATS JetStream · Prometheus · Grafana · OpenTelemetry
**Security & networking:** Wazuh · MikroTik · OWASP Top 10 · PKI / X.509
**Also used:** TypeScript · React · Tailwind CSS · PHP / Laravel · Python · C

