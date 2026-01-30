# System Design Journal

> A weekly deep-dive into high-scale architecture, infrastructure resilience, and the engineering behind the agentic era.

[![System Design](https://img.shields.io/badge/Focus-System%20Design-blueviolet?style=for-the-badge)](https://github.com/Krasper707/system-design-journal)
[![Weekly Updates](https://img.shields.io/badge/Updates-Weekly-green?style=for-the-badge)](https://github.com/Krasper707/system-design-journal)
[![Engineering](https://img.shields.io/badge/Field-SRE%20%26%20DevOps-orange?style=for-the-badge)](https://github.com/Krasper707/system-design-journal)

## The Mission
This journal is a collection of technical retrospectives and architectural case studies. The goal is to move beyond "Hello World" tutorials and analyze how real systems handle **concurrency, failure, and scale.**

---

## Case Study Index

| Week | Case Study | Core Tech | Focus Area |
| :--- | :--- | :--- | :--- |
| **01** | [Scaling AI Agents](./case-studies/2026-01-23-scaling-ai-agents) | `Redis` `LLMs` `Postgres` | Concurrency & Cost Optimization |
| **02** | [Configuration Cascade](./case-studies/2026-01-30-Configuration%20Cascade/Report.md) | `ClickHouse` `Rust` `SRE` | Infrastructure Resilience |

---

## Concepts Explored
I use these case studies to master and document the following architectural patterns:

### Performance & Scale
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) 
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
- **Asynchronous Task Queues:** Decoupling ingestion from execution.
- **Semantic Caching:** Using Vector DBs to kill latency.
- **Model Tiering:** Fiscal sustainability in LLM pipelines.

### Reliability & SRE
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
- **Canary Deployments:** Minimizing blast radius.
- **Circuit Breakers:** Preventing thundering herd failures.
- **Observability:** Cross-referencing audit logs with telemetry.

---

## Roadmap (Upcoming Topics)
- [ ] **Week 03:** Database Sharding: Moving from Monolith to Distributed.
- [ ] **Week 04:** The Anatomy of a Zero-Day: Analyzing Supply Chain Attacks.
- [ ] **Week 05:** Event-Driven Architecture with Kafka.

---

## Author
**Karthik Murali M**  
*Building and breaking systems to understand how the internet stays online.*

[LinkedIn](https://www.linkedin.com/in/m-karthik-murali-3007a6293/) | [Medium](https://medium.com/@karthikmuralim69)
