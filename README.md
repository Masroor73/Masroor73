<div align="center">

![Banner](./Geometric-Banner.png)
 
# Mia Masroor Ahamed
 
**Full-Stack Software Developer**
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mia-masroor-ahamed)
[![Email](https://img.shields.io/badge/Email-wasif4930%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wasif4930@gmail.com)
 
</div>


 
## About
 
Junior full-stack developer and recent SAIT Software Development graduate (June 2026), building reliable backend systems and full-stack web and mobile applications in TypeScript, Go, C# (.NET), and Python. I led a team of 7 to ship a workforce management system for a real Calgary restaurant, built and deployed a webhook reliability gateway on my own, and won awards at two 2026 Calgary hackathons.
 
**Looking for:** Junior Software Developer or Junior Full-Stack Developer roles with product-focused tech teams in Calgary, Alberta.
 
**Awards**
- 🏆 **Best Project Built with ElevenLabs** - IEEE Southern Alberta Young Professionals Industry Hackathon, 2026 ([Pipe Dreams](https://github.com/Masroor73/pipe-dreams))
- 🏆 **Community Choice Award** - Cursor Calgary Hackathon, 2026 (LockInAI: product design and lock-out feature concept)
---
 
## Technical Capabilities & Architecture
 
| Layer | Technologies |
|:---|:---|
| **Languages** | TypeScript, JavaScript, C#, Go, Python, SQL, HTML5, CSS3 |
| **Frameworks** | React, React Native, Next.js, Node.js, .NET, FastAPI |
| **Data** | PostgreSQL, Microsoft SQL Server, Supabase |
| **Cloud & DevOps** | Docker, Google Cloud Run, Microsoft Azure, GitHub Actions |
| **Tools** | Git, REST/OpenAPI, Zod, Figma, UML, Jira, Linear |
 
 
## Featured Projects
 
### [Relay - Webhook Reliability Gateway](https://github.com/Masroor73/relay)
> **Solo Developer · July 2026 – Sept 2026**
 
A self-hostable gateway that sits between a webhook provider (e.g. Stripe) and downstream business logic, guaranteeing every event is durably received, deduplicated, retried on failure, and recoverable if processing fails.
 
**Live:** [Dashboard](https://relay-dashboard-202922425380.us-east4.run.app) · [API](https://relay-server-202922425380.us-east4.run.app)
 
- Go ingestion service with Stripe HMAC-SHA256 signature verification, a Postgres transactional outbox, and database-level idempotency (UNIQUE constraint) so duplicate deliveries cause no duplicate effects
- Exponential-backoff retry (1s to 10m), dead-letter recovery, and a React dashboard for live event status
- MCP server exposing dead-letter inspection and replay as tools, backed by the same API layer as the dashboard
- Root-caused and fixed a self-deadlock in the retry logic and a Postgres container crash-loop
- Deployed on Google Cloud Run (Postgres via Neon); GitHub Actions CI runs lint, build, and tests across all three components plus Trivy container scanning; verified dedup, retry, and replay against the live deployment
`Go` `PostgreSQL` `React` `TypeScript` `Docker` `Google Cloud Run` `GitHub Actions` `MCP`
 
---
 
### [V.A.K - Workforce Management System](https://github.com/Masroor73/vak-monorepo)
> **Technical Lead · Capstone Project for Damascus Fine Mediterranean Foods (Calgary) · Sept 2025 – June 2026**
 
A workforce management system built for a real Calgary restaurant client, replacing generic scheduling. Led a team of 7 from requirements to a working MVP shipped May 2026.
 
- Led system design, tech-stack and architecture decisions, task breakdown and planning, code reviews, unblocking teammates, and client communication
- Owned the Supabase (PostgreSQL) backend: designed the data model and table structure and implemented Row Level Security
- Built a .NET 8 payroll microservice on Azure Functions implementing Alberta's 8/44 overtime rule, kept separate from the rest of the app
- Built an AI waste log: staff photograph food they are discarding and the Google Gemini API identifies and records it, showing the owner where food cost was leaking
- Contributed to the shared React / React Native codebase for the employee mobile app and manager dashboard
`TypeScript` `C# / .NET 8` `React Native (Expo)` `React` `Supabase` `PostgreSQL` `Azure Functions` `Google Gemini`
 
---
 
### [Pipe Dreams - Water-Main Inspection Planner](https://github.com/Masroor73/pipe-dreams)
> **Backend Developer · IEEE Industry Hackathon 2026 · Best Project Built with ElevenLabs · Oct 2026**
 
Helps a municipal water utility decide where to inspect first, using real Open Calgary data (37,538 historical breaks across 60,740 pipe segments).
 
- Built the full Python/FastAPI backend and planning engine
- Plans were evaluated under a frozen validation protocol; the selected plan captured 24.3% of breaks vs. 20.0% for a count-only baseline on held-out 2023-2025 data
- Defined the architecture and vision for the ElevenLabs voice copilot, which answers questions from the audited plan data (front end and agent built by a teammate from that blueprint)
`Python` `FastAPI` `pandas` `TypeScript` `React` `ElevenLabs`
 
---
 
### ABM College - Web Development
> **Web Developer · Sep 2024 – June 2026**
 
- Maintained and updated the college's WordPress website with the Cornerstone page builder
- Built responsive page layouts in HTML, CSS, and JavaScript to fix mobile display issues the CMS couldn't handle on its own
- Managed Cloudflare for DNS and edge caching, combined with image compression to improve page load speed
- Connected Zoho CRM to the site's lead forms via API integration, automating what had been manual data entry
`WordPress` `JavaScript` `HTML5` `CSS3` `Cloudflare` `Zoho CRM`
 
---
 
## Education
 
**Southern Alberta Institute of Technology (SAIT)** · Calgary, AB
Diploma in Software Development · Graduated June 2026
 
Focus areas: Advanced OOP & Design Patterns (C# / Java) · Relational & NoSQL database systems · Capstone: real-client vertical industry solution · HubSpot Sales Hub certified
 
---
 
<div align="center">
*Let's connect and build something that matters.*
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mia%20Masroor%20Ahamed-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mia-masroor-ahamed)
[![Email](https://img.shields.io/badge/Email-wasif4930%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wasif4930@gmail.com)
 
</div>
 
