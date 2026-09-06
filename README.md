<div align="center">

![Banner](./Geometric-Banner.png)

# Mia Masroor Ahamed

**Full-Stack Software Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mia-ahamed-a07876184/)
[![Email](https://img.shields.io/badge/Email-wasif4930%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wasif4930@gmail.com)

</div>

---

## About

I'm a full-stack developer working mainly in React and .NET, with Go, Azure, and 
GCP in my stack too. My main project is V.A.K., a workforce management app built 
for a real restaurant client in Calgary. I led the system design and built the 
payroll microservice in .NET on Azure Functions, worked across the shared 
React/React Native codebase with a team of 7, and added a feature where workers 
photograph ingredients they're discarding and Google Gemini logs the waste 
automatically. I also did web development and CRM/lead-workflow work at ABM 
College, and I'm HubSpot Sales Hub certified.

**Shipped:** [Relay](https://github.com/Masroor73/relay) - a webhook reliability 
gateway (Go, Postgres, React) with idempotent ingestion, a transactional outbox, 
retry/backoff with dead-letter recovery, and an MCP server for agent-driven DLQ 
operations. Deployed on Google Cloud Run and verified against production, not just 
localhost.

---

## Technical Capabilities & Architecture

| Layer | Technologies |
|:---|:---|
| **Languages** | TypeScript, C#, Go, SQL (PL/pgSQL, T-SQL), JavaScript (ES6+), HTML5, CSS3 |
| **Frameworks & UI** | .NET 10, Node.js, React, React Native (Expo), Next.js |
| **Backend & APIs** | REST APIs, Azure Functions |
| **Cloud & Orchestration** | Docker, Google Cloud Platform (GCP), Microsoft Azure, CI/CD (GitHub Actions) |
| **Databases & State** | PostgreSQL, Microsoft SQL Server, Supabase |
| **Ecosystem** | Git, Zod, Orval, OpenAPI (Swagger), Figma, System Design (UML) |

---

## Featured Projects

### [Relay - Webhook Reliability Gateway](https://github.com/Masroor73/relay)
> **Solo Developer · Complete (6 of 6 milestones)**

A self-hostable gateway that sits between a webhook provider (e.g. Stripe) and 
downstream business logic, guaranteeing every event is durably received, 
deduplicated, retried on failure, and recoverable if processing fails.

**Live:** [Dashboard](https://relay-dashboard-202922425380.us-east4.run.app) · 
[API](https://relay-server-202922425380.us-east4.run.app)

- Go ingestion service with Stripe HMAC-SHA256 signature verification and a 
  Postgres-backed transactional outbox
- Idempotency enforced at the database level via a UNIQUE constraint, confirmed 
  under concurrent load in both testing and production
- Exponential backoff retry (1s→10m) with dead-letter recovery for exhausted 
  events, and a React dashboard for live event status
- MCP server exposing dead-letter inspection and replay as tools, backed by the 
  same API layer as the dashboard - enabling agent-driven operations on top of 
  the reliability guarantees
- Deployed on Google Cloud Run (Postgres via Neon), with CI covering 
  build/lint/test across all three components plus Trivy container vulnerability 
  scanning

`Go` `PostgreSQL` `React` `TypeScript` `Docker` `Google Cloud Run` `GitHub Actions` `MCP`

---

### [V.A.K - Valence, Axiom, Kairos](https://github.com/Masroor73/vak-monorepo)
> **Software Developer & Technical Lead · Capstone Project · Sept 2025 – June 2026**

A workforce management system built for a real Calgary restaurant client, replacing generic scheduling. Led a team of 7 through the full build, from requirements to a working MVP.

- Built a payroll microservice in .NET 8 on Azure Functions, exposing an API to handle Alberta's labour rules (the 8/44 rule)
- Worked across the shared React/React Native codebase connecting the employee mobile app and manager dashboard
- Set up Row Level Security in Supabase (PostgreSQL) so different restaurant locations' data stayed properly separated
- Added a feature where workers photograph ingredients they're discarding, and Google Gemini logs the waste via an API call

`TypeScript` `C# / .NET 10` `React Native (Expo)` `React` `Supabase` `PostgreSQL` `Azure Functions` `Google Gemini`

---

### ABM College - Web Development
> **Web Developer · Sep 2024 – June 2026**

- Improved page load speed by about 30% through image compression and caching
- Built responsive, mobile-first layouts in HTML, CSS, and JavaScript to work around CMS limitations
- Connected Zoho CRM to the site's lead forms via API integration, automating what had been manual data entry

`JavaScript` `HTML5` `CSS3` `Performance Optimization`

---

## Education

**Southern Alberta Institute of Technology (SAIT)** · Calgary, AB
Diploma in Software Development · Graduated June 2026

Focus areas: Advanced OOP & Design Patterns (C# / Java) · Security & DevOps (Row Level Security, CI/CD, threat modeling) · Relational & NoSQL database systems · Capstone: real-client vertical industry solution

---

<div align="center">

*Let's connect and build something that matters.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mia%20Ahamed-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mia-ahamed-a07876184/)
[![Email](https://img.shields.io/badge/Email-wasif4930%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wasif4930@gmail.com)

</div>
