<div align="center">

# Onkar Deokate

**Backend Engineer · Go · Ruby on Rails · PostgreSQL · AWS**

Performance optimization, event-driven systems, and platforms that stay up.

[![Email](https://img.shields.io/badge/Email-onkardeokate@gmail.com-red?style=flat&logo=gmail)](mailto:onkardeokate@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-onkardeokate-blue?style=flat&logo=linkedin)](https://linkedin.com/in/onkardeokate)
[![Location](https://img.shields.io/badge/Location-Pune,_India-green?style=flat&logo=google-maps)](https://maps.google.com/?q=Pune,India)

</div>

---

## Experience

### Software Development Engineer / Full-Stack Engineer
**Mar 2025 – present** · PE-backed PropTech marketplace serving 3M+ students · Pune, hybrid

Platform engineer across five product verticals — Leads, Bookings, Payments, CMS and Inventory — covering backend architecture, database performance, AI integration and internal tooling. Ranked #1 on the company's internal engineering performance system, measured on ticket complexity, delivery rate, cycle time and defect rate.

- **Cut critical API latency by 93%** (6.7s → 450ms) through query optimization, composite indexing, Redis caching and a REST redesign — eliminating production timeouts that were affecting thousands of daily bookings
- **Led the architecture of a dynamic N-level inventory system**, replacing a rigid three-level hierarchy with a runtime-configurable model where any level can act as the business standard unit, so new accommodation structures onboard without code changes
- **Built two internal CRM platforms from scratch**, replacing a third-party SaaS dependency: agent assignment engine, Kanban lead pipeline, WhatsApp/email/call communication stack, and a Plivo WebRTC dialer
- **Shipped a cross-border payment gateway** for India–China transactions, acting as primary technical liaison between company leadership and the payment partner's engineering team
- **Integrated a Gemini document-verification pipeline** into the booking flow, automating identity and accommodation document checks
- **Built a booking state machine** with a live dashboard, reducing manual booking intervention by roughly 80%
- Maintained **99%+ availability** across zero-downtime deployments, with active production incident ownership

### Earlier
- **SDE Intern** — Nissan Digital India · Sep – Oct 2024 · React + JavaScript portal work, Excel-to-visualization tooling, Dockerized data layer, Jenkins CI/CD
- **Cloud Infrastructure & Security Intern** — Celebal Technologies · Jun – Aug 2024 · Azure hub-and-spoke topology, custom DNS forwarding, Azure Firewall routing, SSL offloading on Application Gateway
- **Networking Intern** — CJSC Babilon-Mobile · Jun – Aug 2023 · SMPP protocol implementation and simulation for telecom messaging

---

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Deonkar/Aria"><img src="https://opengraph.githubassets.com/1/Deonkar/Aria" alt="Aria CRM" /></a>

**Go · Next.js · PostgreSQL · pgvector**

Student-housing CRM whose AI assistant answers plain-English questions by generating and running **read-only SQL** against a live Postgres database, streaming results over SSE. A schema pipeline keeps the model's view of the database current; the execution path is read-only by construction, so generated SQL can never mutate data.

</td>
<td width="50%" valign="top">

<a href="https://github.com/Deonkar/txFlow"><img src="https://opengraph.githubassets.com/1/Deonkar/txFlow" alt="TxFlow" /></a>

**Kafka · FastAPI · PostgreSQL · Redis**

Payment event orchestrator. One `POST /payment` produces a single Kafka event that five independent consumer groups process — fraud, wallet, notifications, audit, analytics. At-least-once delivery handled properly: retries, Redis-backed deduplication, and a dead-letter queue with its own handler service.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Deonkar/FlowForge"><img src="https://opengraph.githubassets.com/1/Deonkar/FlowForge" alt="FlowForge" /></a>

**Next.js · TypeScript · AWS SQS · Drizzle**

Visual AI workflow automation platform. Decoupled event-driven execution over a message bus rather than direct calls, so trigger sources and the consumer scale independently, wrapped in a retry + circuit-breaker resilience layer. Drag-and-drop React Flow canvas, natural-language workflow generation, TypeScript code export, and a plugin system with 11 integrations.

</td>
<td width="50%" valign="top">

<a href="https://github.com/Deonkar/parkease"><img src="https://opengraph.githubassets.com/1/Deonkar/parkease" alt="ParkEase" /></a>

**NestJS · PostGIS · Turborepo · Expo**

Peer-to-peer parking marketplace for India: drivers book parking, owners monetise unused slots, valet and car-wash services layer on top. Turborepo monorepo, NestJS on Fastify, PostgreSQL 18 + PostGIS for geospatial search, pg-boss worker with a transactional outbox, Zod contracts shared across API, mobile, admin and OpenAPI.

</td>
</tr>
</table>

**Currently building — Company/OS:** a plug-and-play AI operating layer that embeds into an existing CRM, with a business knowledge graph and layered memory (global → company → department → user → conversation). LightRAG, Graphiti, LangGraph and Temporal behind a FastAPI backend.

---

## Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Backend:** Go, Ruby on Rails, Python, FastAPI, NestJS, PostgreSQL, Redis, Sidekiq, Kafka, REST APIs
**Frontend:** React, Next.js, TypeScript, Tailwind CSS
**Infrastructure:** AWS (S3, RDS, EC2, SQS, Lambda), Azure, Docker, Docker Compose, CI/CD

---

## Education & Certifications

**B.Tech, Computer & Communication Engineering** — Manipal University Jaipur · 2021 – 2025 · CGPA 8.44

Certified in **Google Professional Cloud Security Engineer** and **AWS Security Specialty**, among others.

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
