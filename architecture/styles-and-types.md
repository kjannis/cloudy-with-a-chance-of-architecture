# 🏗 Software Architecture Overview

This document outlines key software architecture **styles** and **types**, along with curated resources for deeper learning.

---

## 🔷 Architecture Styles

Architecture styles describe high-level strategies for organizing systems and services.

---

### 🧱 Monolithic

A single deployable unit. Simple to develop and deploy initially, but grows difficult to scale and maintain over time.

**🔗 Resources:**
- [MonolithFirst – Martin Fowler](https://martinfowler.com/bliki/MonolithFirst.html)
- [Why Start with a Monolith – YouTube](https://www.youtube.com/watch?v=kKjm4ehYiMs)
- *Building Microservices* – Sam Newman

---

### 🏢 Layered (N-Tier)

Organizes software into layers such as UI, business logic, and data. Promotes separation of concerns.

**🔗 Resources:**
- [Clean Architecture – Robert C. Martin](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
- *Patterns of Enterprise Application Architecture* – Martin Fowler

---

### 🌐 Service-Oriented Architecture (SOA)

Uses loosely-coupled, reusable services that follow standard protocols. Common in enterprise environments.

**🔗 Resources:**
- *SOA: Principles of Service Design* – Thomas Erl  
- [SOA vs Microservices – ThoughtWorks](https://www.thoughtworks.com/insights/blog/microservices-vs-soa)
- [IBM Guide to SOA](https://www.ibm.com/cloud/learn/soa)

---

### 🧩 Microservices

Architecture based on small, independently deployable services aligned with business domains.

**🔗 Resources:**
- [Microservices.io](https://microservices.io/)
- *Building Microservices* – Sam Newman
- [Monolith vs Microservices – Google Cloud](https://cloud.google.com/learn/monolith-vs-microservices)

---

### ⚡️ Event-Driven Architecture (EDA)

Components communicate through events. Encourages reactive, decoupled systems.

**🔗 Resources:**
- [Event-Driven Architecture – Martin Fowler](https://martinfowler.com/articles/201701-event-driven.html)
- [EventBridge on AWS](https://docs.aws.amazon.com/eventbridge/latest/userguide/what-is-eventbridge.html)
- *Designing Event-Driven Systems* – Ben Stopford

---

### 🛠 Serverless

Runs code in response to events, without provisioning servers. Scales automatically.

**🔗 Resources:**
- [What is Serverless? – AWS](https://aws.amazon.com/serverless/)
- [Serverless Handbook](https://serverlesshandbook.dev/)
- *Serverless Architectures on AWS* – Peter Sbarski

---

### 🧱 Modular Monolith

A monolith organized into independent, well-structured modules. Offers a migration path to microservices.

**🔗 Resources:**
- [Modular Monoliths – Simon Brown](https://www.infoq.com/presentations/modular-monoliths/)
- [Monolith vs Modular Monolith vs Microservices – Dev.to](https://dev.to/nsebhastian/monolith-vs-modular-monolith-vs-microservices-1e5n)

---

## 🔷 Architecture Types

Architecture types describe structural blueprints for how software is composed and interacts.

---

### 🧃 Hexagonal Architecture (Ports & Adapters)

Separates business logic from infrastructure. Uses ports for abstraction and adapters for implementation.

**🔗 Resources:**
- [Alistair Cockburn – Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/)
- [Hexagonal Architecture – Baeldung](https://www.baeldung.com/cs/hexagonal-architecture)

---

### 🧠 Domain-Driven Design (DDD)

Focuses on modeling complex domains and aligning software design closely with business logic.

**🔗 Resources:**
- [Domain-Driven Design – Eric Evans](https://domainlanguage.com/)
- [DDD Reference Site](https://dddreference.com/)
- *Implementing Domain-Driven Design* – Vaughn Vernon

---

### 🔀 Client-Server

A distributed model where the client requests resources/services from a centralized server.

**🔗 Resources:**
- [Client-Server Overview – MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Client-Server_overview)
- [Client-Server Explained – GeeksforGeeks](https://www.geeksforgeeks.org/client-server-architecture/)

---

### 🔂 Peer-to-Peer

Each node can act as both a client and a server. Useful in decentralized systems like file sharing and blockchain.

**🔗 Resources:**
- [Peer-to-Peer Overview – IBM](https://www.ibm.com/docs/en/zos/2.1.0?topic=overview-peer-peer-architecture)
- [Client vs Peer-to-Peer – TechDifferences](https://techdifferences.com/difference-between-client-server-and-peer-to-peer-network.html)

---

### 📦 Plugin Architecture

System designed to accept interchangeable modules or plugins at runtime or startup.

**🔗 Resources:**
- [Designing Plugin Systems – GitHub Engineering](https://github.blog/2020-06-22-designing-a-plugin-system/)
- [Plugin Architecture in Java – DZone](https://dzone.com/articles/building-a-plugin-architecture-in-java)

---

### ⚙️ Event Sourcing

System stores state as a sequence of events rather than current state.

**🔗 Resources:**
- [Event Sourcing – Martin Fowler](https://martinfowler.com/eaaDev/EventSourcing.html)
- *Event Sourcing* – Greg Young
- [Azure Architecture – Event Sourcing Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)

---

### ➕ CQRS (Command Query Responsibility Segregation)

Separates command (write) and query (read) operations into distinct models.

**🔗 Resources:**
- [CQRS – Martin Fowler](https://martinfowler.com/bliki/CQRS.html)
- [CQRS Pattern – Microsoft Azure](https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs)
- *Hands-On Domain-Driven Design with .NET Core* – Alexey Zimarev

---

