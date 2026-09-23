<div align="center">

# Onkar Deokate

**Backend Engineer · Go · Ruby on Rails · PostgreSQL · AWS**

[![Email](https://img.shields.io/badge/Email-onkardeokate@gmail.com-red?style=flat&logo=gmail)](mailto:onkardeokate@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-onkardeokate-blue?style=flat&logo=linkedin)](https://linkedin.com/in/onkardeokate)
[![Location](https://img.shields.io/badge/Location-Pune,_India-green?style=flat&logo=google-maps)](https://maps.google.com/?q=Pune,India)

</div>

---

## About Me

Backend engineer working on performance optimization and event-driven systems. I build production platforms that handle millions of records, and spend most of my time on the part where they have to keep working under load.

**In production:**
- 93% API latency reduction (6.7s to 450ms) on the core lead pipeline
- >99% reduction in database timeouts (60s to 450ms)
- CRM serving 3M+ records across 480+ concurrent agents
- Zero-downtime deployments
- 100+ production incidents resolved as on-call engineer

---

## Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Backend:** Go, Ruby on Rails, Python, PostgreSQL, Redis, Sidekiq, Kafka, REST APIs
**Frontend:** React, Next.js, TypeScript, Tailwind CSS
**Infrastructure:** AWS (S3, RDS, EC2), Docker, Docker Compose, CI/CD

---

## Featured Work

### [Aria CRM](https://github.com/Deonkar/Aria) — Go · Next.js · PostgreSQL
Student-housing CRM with an AI assistant that answers questions in plain English by generating and running read-only SQL against a live Postgres database, streaming results over SSE.
- **Stack:** Go API, Next.js, PostgreSQL + pgvector, Redis, Docker Compose
- **Interesting bit:** a schema pipeline that keeps the model's view of the database in sync, and a read-only execution path so generated SQL can never mutate data

### [TxFlow](https://github.com/Deonkar/txFlow) — Kafka · FastAPI · PostgreSQL
Payment event orchestrator. One `POST /payment` produces a single Kafka event that five independent consumer groups process: fraud, wallet, notifications, audit, analytics.
- **Stack:** Redpanda/Kafka, FastAPI, PostgreSQL, Redis, Docker Compose, Next.js dashboard
- **Interesting bit:** at-least-once delivery handled properly — retries, Redis-backed deduplication, and a dead-letter queue with its own handler service

### [ParkEase](https://github.com/Deonkar/parkease) — NestJS · PostGIS · Expo
Peer-to-peer parking marketplace for India: drivers book parking, owners monetise unused slots, valet and car-wash services layer on top.
- **Stack:** Turborepo monorepo, NestJS on Fastify, PostgreSQL 18 + PostGIS, Drizzle ORM, Expo, Next.js
- **Status:** in active development — architecture and contracts first, Zod schemas shared across API, mobile, admin and OpenAPI

### [FlowForge](https://github.com/Deonkar/FlowForge) — Next.js · Workflow DevKit
Visual AI workflow builder: a drag-and-drop canvas that compiles workflows into executable TypeScript, with real integrations and execution logging.
- **Stack:** Next.js, React Flow, Drizzle ORM, PostgreSQL, Better Auth
- **Interesting bit:** generated code is type-safe and runnable, not a config blob — workflows become real functions

### Internal CRM Platform — production, closed source
Rails + React CRM managing 3M+ leads for 480+ concurrent agents. Where the latency and uptime numbers above come from.
- **Stack:** Ruby on Rails, React, PostgreSQL, Redis, Sidekiq, AWS S3

---

## Currently Learning

- Distributed systems patterns (CQRS, event sourcing)
- Kubernetes and cloud-native architecture
- Advanced PostgreSQL optimization and query planning

---

## Get in Touch

**Open to:** backend and SDE roles, Go and Rails especially — performance work, platform and internal tooling, event-driven systems.

**Based in** Pune, India. Open to Pune, Mumbai, Hyderabad, remote, and relocation.

📧 **Email:** onkardeokate@gmail.com
💼 **LinkedIn:** [linkedin.com/in/onkardeokate](https://linkedin.com/in/onkardeokate)
