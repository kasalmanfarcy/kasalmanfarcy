<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Salman+Farcy+%F0%9F%91%8B;Backend+%26+AI+Engineer;Java+%7C+Spring+Boot+%7C+Python+%7C+FastAPI+%7C+Kafka;Agentic+AI+Workflows+on+Azure+OpenAI" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/salmanfarcyka"><img src="https://img.shields.io/badge/LinkedIn-salmanfarcyka-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:salmanfarcyka@gmail.com"><img src="https://img.shields.io/badge/Email-salmanfarcyka%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

```yaml
name        : Salman Farcy
role        : Backend Software Engineer
company     : Qubit Capital (Fintech)
experience  : 2 years — fintech backends & AI-powered platforms
focus       : Java/Spring Boot · Python/FastAPI · Kafka · Agentic AI · API security
location    : India — open to relocate (Singapore · UAE · Europe)
```

## About me

Backend engineer with 2 years of production experience in fintech. I build event-driven microservices in
**Java/Spring Boot** and AI-powered platforms in **Python/FastAPI**, and I own work end to end — design,
implementation, deployment and production support.

- Led a **zero-downtime migration** of a monolith into **12 event-driven microservices** (60+ versioned REST endpoints)
- Cut a **2M+ record API from 2 s to 800 ms** through query optimisation and database tuning
- Built **10 agentic AI workflows** on Azure OpenAI (GPT-5, GPT-4o) and Azure AI Foundry with LangChain, tool calling and MCP

## Tech stack

**Languages:** Java 17/25 · Python · SQL<br>
**Backend:** Spring Boot · Spring Security · FastAPI · REST APIs · Microservices · Event-Driven Architecture<br>
**Messaging & data:** Apache Kafka · PostgreSQL · MySQL · MongoDB · Redis<br>
**AI & LLMs:** Azure OpenAI · Azure AI Foundry · LangChain · MCP · Function / Tool Calling<br>
**Cloud & DevOps:** Docker · Kubernetes · Azure · GitHub Actions · Linux · Nginx<br>
**Security & testing:** JWT · OAuth 2.0 · RBAC · JUnit · Testcontainers · PyTest

## Featured work

### ReconFlow — multi-tenant payment reconciliation platform *(personal project)*
`Java 25` `Spring Boot 4` `PostgreSQL RLS` `Flyway` `Keycloak OIDC` `Testcontainers` `GitHub Actions` `Prometheus`
- Idempotent reconciliation engine: every ledger/settlement record is classified as matched, amount mismatch, missing or duplicate; property-based tests prove each record lands in exactly one outcome
- Exception workflow with RBAC, optimistic locking (HTTP 409 on concurrent edits) and an append-only audit trail written in the same transaction
- Tenant isolation with PostgreSQL row-level security and cross-tenant tests on every endpoint; RS256 JWT with rotating refresh tokens and reuse detection

### Real-time transaction risk-scoring platform *(personal project)*
`Java 17` `Spring Boot` `Apache Kafka` `Redis` `PostgreSQL` `MongoDB` `Docker` `Kubernetes`
- Partitioned Kafka consumers with a bounded thread pool feeding a modular, auditable rule engine for explainable fraud flagging
- Atomic Redis operations for race-free per-account velocity tracking under bursts

### Agentic AI workflows @ Qubit Capital
- 10 production workflows on Azure OpenAI and Azure AI Foundry with LangChain: investor-email drafting, investor research, lead and email automation, sales-call insights
- Function/tool calling and MCP integrations with internal systems

### AI sales-call insights platform @ Qubit Capital
- Python/FastAPI platform orchestrating AI agents to deliver post-call insights and metrics **within 1 minute**
- Used on **3,500+ sales calls** across **30+ users**

### Investor intelligence pipelines @ Qubit Capital
- Replaced a paid startup–investor mapping tool with in-house pipelines over **100K+ investor records**, removing the recurring subscription cost

### Production API suite @ Qubit Capital *(internship)*
- Shipped **12+ REST APIs** for AI-agent workflows (Azure AI, Perplexity APIs), cutting manual work by up to 90%
- Selenium + BeautifulSoup ingestion pipelines into Azure Blob Storage that fully replaced manual data gathering

## How I work

- Own features end to end — system design → implementation → production
- Correctness first: idempotency, audit trails, tests that prove invariants
- If something can be automated reliably, it gets automated

<p align="center">
  <a href="https://linkedin.com/in/salmanfarcyka">LinkedIn</a> ·
  <a href="mailto:salmanfarcyka@gmail.com">Email</a>
</p>
