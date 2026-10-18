# Hi, I'm Amal 👋

**Full-stack software engineer in Cairo, Egypt.** I build backend systems that stay correct at volume (batch jobs, queues, integrations, database performance) and the React products on top of them.

[![Portfolio](https://img.shields.io/badge/Portfolio-A855F7?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-amaleltelbany.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amal-eltelbany-7a5470204/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amal.eltelbany.2002@gmail.com)
[![CV](https://img.shields.io/badge/Download_CV-22C55E?style=flat-square&logo=adobeacrobatreader&logoColor=white)](./Amal_Eltelbany_CV.pdf)

## What I'm doing now

- 💼 **Full-Stack Engineer at Fincart**: campaign processing, courier integrations, Shopify apps and merchant dashboards
- 🤖 **Building an AI customer-support platform** (WhatsApp + web widget) to go deep on LLM agents, RAG and evals
- 🎯 **Open to** mid-level full-stack and backend roles, Cairo or remote

## Highlights from production

- **~500× fewer database calls** when building campaign audiences for merchants with 500k+ contacts (cursor-paged batch inserts, crash-safe re-runs) · NestJS, Prisma, PostgreSQL
- **4,282 → 1 documents read** per order lookup after designing compound MongoDB indexes
- **6 courier integrations, 1 gateway**: leading the migration of Aramex, Bosta, FedEx, J&T, Turbo and YFS onto a shared courier gateway
- **One engine, two products**: a canvas-based automation builder (React Flow) with custom auto-layout, reused to launch Campaigns
- **Server-trusted Shopify checkout**: customer data resolved on the server with session-token validation

## Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**Resilient Event Gateway**](https://github.com/AmalEltelbany?tab=repositories) | Webhook ingestion on the transactional outbox pattern: HMAC verification, 4 idempotency layers, backoff retries, dead-letter queue. **p95 77ms, zero lost events at a 20% downstream failure rate.** | NestJS · MongoDB · Redis · BullMQ · Docker |
| [**AI Support Platform**](https://github.com/AmalEltelbany/ai-support-platform) *(in progress)* | Multi-tenant AI customer support for WhatsApp and a web widget | Next.js · NestJS · Turborepo · LLMs |
| **Sign Language Translator** | Graduation project (A+): two-way sign/text/speech translation, BiLSTM at 93.7% accuracy, real-time in video calls | Flask · TensorFlow |

## Tech I use day to day

[![Tech](https://skillicons.dev/icons?i=ts,nodejs,nestjs,postgres,prisma,mongodb,redis,react,nextjs,redux,tailwind,docker,githubactions,vitest&perline=7)](https://skillicons.dev)

## Ask me about

Idempotency and the outbox pattern · MongoDB and PostgreSQL indexing · batch processing at scale · React Flow · RTL (Arabic/English) UIs
