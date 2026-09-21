# Kexun Liu

### Backend Engineering · Distributed Systems · Financial Technology

MSc Computer Science, University College Dublin — First Class Honours

Dublin, Ireland

## About

I'm a backend-focused software engineer working across **Java, Spring Boot, Python, distributed systems, and financial data platforms**.

My recent work focuses on building event-driven backend systems, distributed infrastructure, and evidence-grounded AI applications. I have hands-on experience with **Spring Boot microservices, RabbitMQ, Redis, PostgreSQL/MySQL, gRPC, Docker, Kubernetes, AWS, and RAG pipelines**.

Before moving fully into software engineering, I worked in structured finance at a credit rating company in Shanghai, where I supported internal financial systems, data migration, workflow design, and production rollout for platforms used by 150+ analysts.

## Featured Projects

### Financial Intelligence Platform

A financial intelligence platform that ingests SEC EDGAR/XBRL data and transforms filings into structured financial data, analytics, and evidence-grounded risk analysis.

- Built Spring Boot services for SEC data ingestion, normalization, persistence, and downstream analytics.
- Designed an event-driven processing pipeline using **RabbitMQ**, **Redis**, **MySQL**, and **Flyway**.
- Built a RAG pipeline over SEC filings with **claim-level evidence verification** and abstention when evidence is insufficient.
- Containerized and deployed backend services on **AWS EC2** using Docker Compose.
- Added automated testing across service and API layers.

**Tech:** Java · Spring Boot · Python · MySQL · Redis · RabbitMQ · Docker · AWS · RAG

---

### Distributed Systems & Resilience Engineering

Hands-on distributed systems experiments covering communication, replication, consistency, resilience, and orchestration.

- Implemented and benchmarked **TCP sockets, REST, and gRPC/Protobuf** across containerized services.
- Built a **3-node MongoDB replica set** to evaluate replication, write concerns, consistency, failover, and leader re-election.
- Implemented **circuit breaker, timeout, retry, exponential backoff, and jitter**.
- Deployed services on **Kubernetes** to test service discovery, replicas, load balancing, and failure recovery.

**Tech:** Python · gRPC · Protobuf · MongoDB · Docker · Kubernetes

---

### OrderFlow

An event-driven food ordering backend built with Spring Boot, PostgreSQL, Redis, and RabbitMQ.

- Built four backend services spanning **User, Restaurant, Order, and Payment** domains.
- Designed an asynchronous **order-payment workflow** using RabbitMQ events.
- Implemented payment idempotency and order state transitions for successful and failed payments.
- Used Redis for shopping carts, TTL-based expiration, duplicate-submission protection, and popularity ranking.
- Added unit, controller, API, repository, and messaging integration tests using **JUnit 5, Mockito, MockMvc, and Testcontainers**.

**Tech:** Java · Spring Boot · PostgreSQL · Redis · RabbitMQ · Docker · Testcontainers

## Professional Experience

### Credit Rating Analyst  
**China Chengxin Credit Rating Company · Shanghai, China**  
Sep 2021 – Aug 2023

Worked at the intersection of structured finance, financial data, and internal technology systems.

- Built a Python rule-based validation tool for rating reports, reducing pre-QC review time from approximately **10–15 minutes to 1–2 minutes per report**; the tool was adopted as a mandatory check across around **1,000 reports**.
- Supported the rollout of an internal rating platform used by **150+ users**, translating rating and approval workflows into system requirements.
- Cleaned, deduplicated, reconciled, and validated approximately **2,000 legacy MySQL records** for migration.
- Participated in workflow validation, UAT, production rollout, and ongoing system/data support.

## Engineering Focus

**Backend Engineering**  
Java · Spring Boot · Python · FastAPI · REST APIs · Microservices

**Distributed Systems**  
RabbitMQ · Redis · gRPC · Replication · Fault Tolerance · Event-Driven Architecture

**Data**  
PostgreSQL · MySQL · MongoDB · SQL · Financial Data Processing

**Cloud & DevOps**  
AWS · Docker · Kubernetes · Git · CI/CD

**Testing**  
JUnit 5 · Mockito · MockMvc · Testcontainers

**AI & LLM Applications**  
RAG · Embeddings · Vector Search · Evidence Verification

## Currently Exploring

- Reliable messaging and distributed transaction patterns
- Financial data platforms
- Backend reliability and observability
- Evidence-grounded AI systems
- Cloud deployment and production engineering

## Contact

LinkedIn · GitHub · Email
