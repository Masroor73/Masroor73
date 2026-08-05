<div align="center">

![Banner](./Geometric-Banner.png)

# Mia Masroor Ahamed

**Full-Stack Software Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mia-ahamed-a07876184/)
[![Email](https://img.shields.io/badge/Email-wasif4930%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wasif4930@gmail.com)

</div>

---

## About

I'm a full-stack developer working mainly in React and .NET, with Azure and GCP in my stack too. My main project is V.A.K., a workforce management app built for a real restaurant client in Calgary. I led the system design and built the payroll microservice in .NET on Azure Functions, worked across the shared React/React Native codebase with a team of 7, and added a feature where workers photograph ingredients they're discarding and Google Gemini logs the waste automatically. I also did web development and CRM/lead-workflow work at ABM College, and I'm HubSpot Sales Hub certified.

**Currently building:** [Relay](https://github.com/Masroor73/relay) - a webhook reliability gateway (Go, Postgres, React) - in progress, Milestone 1 of 6 complete.

---

## Technical Capabilities & Architecture

| Layer | Technologies |
|:---|:---|
| **Languages** | TypeScript, C#, SQL (PL/pgSQL, T-SQL), JavaScript (ES6+), HTML5, CSS3 |
| **Frameworks & UI** | .NET 10, Node.js, React, React Native (Expo), Next.js |
| **Backend & APIs** | REST APIs, Azure Functions |
| **Cloud & Orchestration** | Docker, Google Cloud Platform (GCP), Microsoft Azure, CI/CD (GitHub Actions) |
| **Databases & State** | PostgreSQL, Microsoft SQL Server, Supabase |
| **Ecosystem** | Git, Zod, Orval, OpenAPI (Swagger), Figma, System Design (UML) |

---

## Featured Projects

### [Relay - Webhook Reliability Gateway](https://github.com/Masroor73/relay)
> **Solo Developer · In Progress (Milestone 1 of 6 complete)**

A self-hostable gateway that sits between a webhook provider (e.g. Stripe) and downstream business logic, guaranteeing every event is durably received, deduplicated, retried on failure, and recoverable if processing fails.

**What's built so far (Milestone 1 - Ingestion + Schema):**
- Go ingestion service with inline Stripe HMAC-SHA256 signature verification
- Postgres schema for events, outbox, dead-letter, and orders tables
- Request size limiting, in-memory rate limiting, explicit DB connection pool limits
- Structured JSON logging with correlated event IDs across every log line
- CI pipeline (build + lint) and local dev via Docker Compose

**What's next:** transactional outbox + concurrent idempotency dedup, retry/backoff processor with dead-letter recovery, a React dashboard, and an MCP server for programmatic dead-letter inspection.

`Go` `PostgreSQL` `React` `TypeScript` `Docker` `Google Cloud Run` `GitHub Actions`

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
