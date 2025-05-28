# 🔁 Architecture Reliability

Ensuring systems remain available, consistent, and fault-tolerant under various conditions.

---

## ⚖️ Core Concepts

| Concept         | Description |
|-----------------|-------------|
| **Availability** | Uptime; system continues to operate |
| **Resilience**   | Recovery from failure |
| **Redundancy**   | Backup components/systems |
| **Consistency**  | Ensuring correct data/state |
| **Fault Tolerance** | Continue despite faults |

---

## 🧠 Design Strategies

- Graceful degradation & circuit breakers
- Retry with backoff & idempotency
- Distributed tracing and observability
- Data replication and failover
- Chaos engineering (e.g., Netflix's Chaos Monkey)

---

## 🧰 Tools

- Istio / Envoy for resilience patterns
- Prometheus + Grafana for monitoring
- AWS Route 53 for failover routing
- Kubernetes Liveness/Readiness probes
- Chaos Toolkit / Gremlin for fault injection

---

## 📚 Resources

- [AWS Well-Architected: Reliability](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/)
- [Resilient Systems – Martin Kleppmann](https://martin.kleppmann.com/papers/reliable-messaging.pdf)
- [Principles of Chaos Engineering](https://principlesofchaos.org/)
- *Site Reliability Engineering – Google SRE Book* ([sre.google](https://sre.google/books/))

