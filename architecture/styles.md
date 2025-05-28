# 🏗 Architecture Styles

Common ways of organizing and structuring software systems based on principles, goals, and patterns.

---

## 🧱 Monolithic

A single deployable unit, easy to develop and test early on. Becomes harder to scale and evolve.

### 🔗 Resources
- [MonolithFirst – Martin Fowler](https://martinfowler.com/bliki/MonolithFirst.html)
- [Why Start with a Monolith – YouTube](https://www.youtube.com/watch?v=kKjm4ehYiMs)
- *Building Microservices* – Sam Newman (Chapter: "Monoliths")

---

## 🏢 Layered (N-Tier)

Organizes code into UI, business, and data layers. Encourages separation of concerns.

### 🔗 Resources
- [Clean Architecture – Robert C. Martin](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
- *Patterns of Enterprise Application Architecture* – Martin Fowler

---

## 🌐 Service-Oriented Architecture (SOA)

Loosely-coupled services using shared standards. Often used in enterprise ecosystems.

### 🔗 Resources
- *SOA: Principles of Service Design* – Thomas Erl
- [SOA vs Microservices – ThoughtWorks](https://www.thoughtworks.com/insights/blog/microservices-vs-soa)
- [What is SOA? – IBM](https://www.ibm.com/cloud/learn/soa)

---

## 🧩 Microservices

Independent, domain-aligned services that scale autonomously. Increases operational complexity.

### 🔗 Resources
- [Microservices.io](https://microservices.io/)
- *Building Microservices* – Sam Newman
- [Microservices vs Monolith – Google Cloud](https://cloud.google.com/learn/monolith-vs-microservices)

---

## ⚡️ Event-Driven Architecture (EDA)

Systems communicate using events, improving decoupling and scalability.

### 🔗 Resources
- [Event-Driven Architecture Patterns – Martin Fowler](https://martinfowler.com/articles/201701-event-driven.html)
- [Event-Driven Architecture Explained – AWS](https://docs.aws.amazon.com/eventbridge/latest/userguide/what-is-eventbridge.html)
- *Designing Event-Driven Systems* – Ben Stopford

---

## 🛠 Serverless

Run code without managing servers. Good for bursty workloads.

### 🔗 Resources
- [What is Serverless? – AWS](https://aws.amazon.com/serverless/)
- [Serverless Handbook](https://serverlesshandbook.dev/)
- *Serverless Architectures on AWS* – Peter Sbarski

---

## 🏗 Modular Monolith

Logically separated modules within a single deployable unit. A middle ground between monolith and microservices.

### 🔗 Resources
- [Modular Monoliths – Simon Brown](https://www.infoq.com/presentations/modular-monoliths/)
- [Monolith vs Modular Monolith vs Microservices – Dev.to](https://dev.to/nsebhastian/monolith-vs-modular-monolith-vs-microservices-1e5n)
