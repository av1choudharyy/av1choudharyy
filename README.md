# Hi there, I'm Abhishek Choudhary

## Founder of [Aryra](https://aryra.in) | Senior Software Engineer

Currently building **Aryra** — an AI-powered assistant combining multimodal analysis, agentic reasoning, semantic search, sandboxed code execution, and inline content generation in a single streaming interface.

### About Aryra

[Aryra](https://aryra.in) is a production AI platform featuring:
- **Custom ReAct Agent**: 33-tool agent loop (no LangChain/LangGraph), real-time SSE streaming of reasoning and Plotly charts
- **Provider Abstraction**: Single env var switches entire cloud stack — AWS (S3 + Textract + Bedrock + Transcribe) or GCP (GCS + Cloud Vision + Vertex + Google Transcribe), with per-service overrides. LLM layer supports Anthropic, AWS Bedrock, Google Vertex AI (Claude + Gemini), OpenAI, and Ollama under a unified interface
- **Knowledge Bank & HNSW**: pgvector semantic search with HNSW indexing for sub-millisecond nearest-neighbor lookup, HyDE query expansion, auto-caching of every Q&A pair as embeddings for progressive knowledge enrichment
- **Multimodal Asset Analysis**: Image OCR (Textract or Cloud Vision), PDF page-level extraction with per-page embeddings, Excel chunked processing, audio transcription (AWS or Google Cloud Speech), video analysis via native Bedrock video blocks (s3Location, Nova Pro)
- **Inline Image & Video Generation**: Abstract GenerationProvider (Bedrock, OpenAI DALL-E, Google Imagen) — generate images and videos directly in chat, streamed as file uploads
- **NL2SQL**: Schema-aware natural language to SQL with automatic schema discovery, TTL-cached metadata, and 20+ injection pattern blocks
- **File Management & Deduplication**: SHA-256 hash-based deduplication across S3/GCS, proxied downloads, semantic file search, storage lifecycle tiering
- **Redis Caching**: Abstract CacheBackend (Redis + NullCacheBackend fallback), TTL-aware schema deduplication, semantic query caching
- **Self-Hosted Observability**: OpenTelemetry (FastAPI + asyncpg instrumented) → Grafana Alloy → Loki (logs) + Tempo (traces) + Prometheus (metrics) + Grafana dashboards
- **Session Sharing & Forking**: Fork any conversation from any message, token-based sharing, fork chain traversal, bookmarks, real-time SSE notifications
- **IAM-Style RBAC**: JSON policy documents, deny-wins evaluation, role hierarchy, wildcard resource matching across 8 resource groups
- **Sandboxed Python**: subprocess isolation, custom MetaPathFinder blocking 18 dangerous imports, inline Plotly charts, Excel/PDF/PPTX/CSV export
- **Integrations**: Gmail OAuth (12 tools, multi-account), SearXNG + Crawl4AI web search, Google SSO, persistent per-user memory

**Tech Stack**: Python · FastAPI · React 19 · TanStack Start · React Native/Expo · PostgreSQL/pgvector · Redis · AWS Bedrock · GCP Vertex AI · Docker · OpenTelemetry · Grafana

---

## Professional Experience

### Current

**Founder** at [Aryra](https://aryra.in) *(Mar 2025 - Present)*
- Built full agentic AI platform with custom ReAct agent (33 tools), SSE streaming, and multi-LLM routing across Anthropic, AWS Bedrock, Google Vertex AI (Claude + Gemini), OpenAI, and Ollama
- Provider abstraction layer — single env var switches entire cloud stack (AWS or GCP) with per-service overrides
- Self-hosted observability: OTel → Grafana Alloy → Loki + Tempo + Prometheus + Grafana
- React 19 / TanStack Start SSR frontend with pnpm monorepo, Turborepo, and React Native/Expo mobile app

**Senior Software Consultant** at Piping Rock India *(Mar 2025 - Present)*
- Built hybrid OCR + Vision asset analysis API with AWS Textract + Claude Sonnet 4.5 and Amazon Titan V2 embeddings
- Designed LangGraph ReAct agent with 16 tools and Nova Embed V2 (3072-dim) multimodal embedding pipeline
- Deployed FastAPI on AWS Lambda via Docker + SAM with 99-file test suite and full audit logging

### Previous

**Senior Software Engineer** at Headout *(Mar 2024 - Oct 2024)*
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

- Scaling Aryra to a wider user base at [aryra.in](https://aryra.in)
- Expanding provider coverage and fine-tuning multi-LLM routing strategies
- Growing the knowledge bank with richer graph interlinking and smarter context enrichment
