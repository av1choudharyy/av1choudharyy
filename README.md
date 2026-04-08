# Hi there, I'm Abhishek Choudhary

## Founder of [Aryra](https://aryra.in) | Senior Software Engineer

Currently building **Aryra** — an AI assistant that connects to your entire work stack. Chat, research, voice, code execution, file analysis, and enterprise integrations in one place.

---

### About Aryra

[Aryra](https://aryra.in) is an AI assistant built from scratch. Connect your work tools, upload your files, and ask anything — it reads your emails, checks your tickets, reviews pull requests, and searches the web, all from one chat window.

**Chat & Ask**
Ask anything conversational or task-based. Aryra reasons across your connected tools — searching emails, fetching Jira issues, reading Confluence pages, looking up Slack threads — and responds in one clean answer. Attach files (PDFs, images, spreadsheets, audio, video) and it analyzes them inline.

**Deep Research**
Give it a research question and it may ask clarifying questions first, then builds a plan, researches each subtopic in parallel, detects contradictions across sources, reviews quality, catches weak sections, and produces a structured report with cited sources. You watch it work in real time — topics update live as each thread completes. The final report is properly structured with an executive summary, sections, cross-cutting insights, and a source list.

**Talk Mode**
Press the mic and have a natural voice conversation. Aryra detects when you stop speaking automatically — no push-to-talk. It transcribes, thinks, and responds out loud, with each word highlighted as it's spoken. Works for quick questions or extended back-and-forth.

**Connected to your tools**
Connect once and Aryra can act across your entire stack:

| | |
|---|---|
| **Email & Calendar** | Gmail, Google Calendar, Outlook |
| **Communication** | Slack, Microsoft Teams |
| **Dev Tools** | GitHub, GitLab, Bitbucket, Jira, Linear |
| **Docs & Storage** | Confluence, Notion, Google Docs, Google Drive, Google Sheets, OneDrive |
| **CRM** | Salesforce, HubSpot |
| **Support** | Zendesk |
| **Observability** | Datadog, Sentry, PagerDuty |
| **HR** | BambooHR, Workday, greytHR |

**For teams**
Organisations get a shared knowledge platform — every connected tool gets indexed, access-controlled, and made searchable. Ask Aryra about a teammate's PR, a Jira sprint, or a Confluence doc — it knows.

**Built on:**
- Custom agentic loop built from scratch — no LangChain, no LangGraph
- Provider abstraction — one env var switches between AWS and GCP for the entire cloud stack
- pgvector semantic search with HNSW indexing
- Self-hosted observability: OpenTelemetry → Grafana → Loki + Tempo + Prometheus

**Open source tools I've built:**
- [`bitbucket-mcp`](https://github.com/av1choudharyy/bitbucket-mcp) — MCP server for Bitbucket: list, review, and manage PRs
- [`mssql-mcp`](https://github.com/av1choudharyy/mssql-mcp) — MCP server for SQL Server (cross-platform SQL auth + Windows auth)

---

## Professional Experience

### Current

**Founder** at [Aryra](https://aryra.in) *(Jan 2026 - Present)*
- Designed and shipped the full product solo — from landing page and onboarding to billing, org management, settings, and mobile app — without a design or product team
- Launched beta with in-app feedback system, Sentry error tracking, feature gating, and plan-based entitlement (daily quotas, org-pooled limits)
- Built full agentic AI platform with custom ReAct agent, SSE streaming, and multi-LLM routing across Anthropic, AWS Bedrock, Google Vertex AI (Claude + Gemini), OpenAI, and Ollama
- Provider abstraction layer — single env var switches entire cloud stack (AWS or GCP) with per-service overrides
- Deep Research engine: parallel topic agents + director review + citation registry produces structured 3K–15K word reports
- Voice interface: Silero VAD + WebSocket streaming STT + SSML TTS with per-word karaoke highlighting
- Enterprise knowledge platform: per-org data isolation, Neo4j knowledge graph, Dramatiq async workers, hybrid search with ACL filtering
- Self-hosted observability: OTel → Grafana Alloy → Loki + Tempo + Prometheus + Grafana

**Senior Software Consultant** at Piping Rock India *(Mar 2025 - Present)*
- Built hybrid OCR + Vision asset analysis API with AWS Textract + Claude Sonnet 4.5 and Amazon Titan V2 embeddings
- Designed LangGraph ReAct agent with Nova Embed V2 (3072-dim) multimodal embedding pipeline
- Deployed FastAPI on AWS Lambda via Docker + SAM with full audit logging

### Previous

**Senior Software Engineer** at Headout *(Mar 2025 - Oct 2025)*
- Scaled review collection system to 1.5M users with 11.4% increase in submissions
- Designed WhatsApp Business API integration achieving 7.3% collection rate increase
- Led full-stack project with Kotlin microservices, Redis caching, and Mixpanel analytics

**Software Engineer** at Cimpress *(Dec 2023 - Mar 2025)*
- Optimized PostgreSQL queries with 1.4x to 27x performance improvements
- Led UI component development epic for Order Management System
- Designed traceability system with DocumentDB for distributed systems

**Software Developer** at Piping Rock *(Jan 2022 - Dec 2023)*
- Built Warehouse Management System on AWS reducing operational costs by 33%
- Developed custom ORM and WebSocket microservices
- Improved application load times by 20% with database connection pooling

---

## Resume

📄 [**Download Latest Resume (PDF)**](https://github.com/av1choudharyy/resume/releases/latest/download/resume.pdf)

*Auto-generated from the [resume repo](https://github.com/av1choudharyy/resume) on every push to main.*

---

## Tech Stack

**Languages:**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Frontend:**
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TanStack](https://img.shields.io/badge/-TanStack_Start-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![React_Native](https://img.shields.io/badge/-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

**Backend:**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![Nest.js](https://img.shields.io/badge/-Nest.js-E0234E?style=flat-square&logo=nestjs&logoColor=white)

**Databases:**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/-pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)

**AWS:**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Bedrock](https://img.shields.io/badge/-Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![Textract](https://img.shields.io/badge/-Textract-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

**GCP:**
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Vertex_AI](https://img.shields.io/badge/-Vertex_AI-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Cloud_Vision](https://img.shields.io/badge/-Cloud_Vision-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Cloud_Storage](https://img.shields.io/badge/-Cloud_Storage-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

**AI Providers:**
![Anthropic](https://img.shields.io/badge/-Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**DevOps & Observability:**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI/CD-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/av1choudharyy)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:choudharyabhishek2199@gmail.com)

---

## Current Focus

- Running Aryra's beta at [aryra.in](https://aryra.in)
- Building enterprise knowledge platform — org-connected AI that indexes your entire company
- Open source MCP servers for developer tooling ([bitbucket-mcp](https://github.com/av1choudharyy/bitbucket-mcp), [mssql-mcp](https://github.com/av1choudharyy/mssql-mcp))
