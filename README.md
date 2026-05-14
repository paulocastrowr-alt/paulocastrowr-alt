# Marcio Paulo

**Founder @ Vox Solutions · AI Systems Engineer · SaaS Architect**

I build production-grade intelligent systems where AI, automation, and software converge — transforming fragmented business operations into integrated, self-running products.

My work lives at the intersection of LLM engineering, workflow automation, and full-stack development. I don't prototype ideas — I ship them.

---

## What I actually build

**End-to-end AI agents** that handle real business workflows — from receiving a WhatsApp message to updating a CRM, triggering a payment, scheduling a meeting, and notifying the right person. No human in the loop unless it adds value.

**Multi-tenant SaaS platforms** designed from the ground up for scale — isolated data per tenant, role-based auth, billing, webhooks, and white-label support. Architecture decisions that survive the jump from 1 to 1,000 clients.

**Document intelligence pipelines** that ingest unstructured inputs — CAD files, PDFs, spreadsheets — and return structured, actionable data. Currently: DWG architectural drawings analyzed via Autodesk APS + Claude Vision, outputting standardized budget parameters.

**Automation infrastructure** that replaces manual operations across sales, marketing, and back-office — n8n workflows connected to LLMs, messaging APIs, CRMs, and payment systems.

---

## Current work

| Project | Description | Stack |
|---|---|---|
| **Vox Platform CRM** | Multi-tenant SaaS CRM — WhatsApp inbox, AI insights, pipeline, campaigns, billing | Next.js 14 · Supabase · TypeScript · Vercel |
| **AI Agent — SDR** | Conversational sales agent on WhatsApp — qualifies leads, handles objections, books meetings via Calendar API | n8n · Claude API · Evolution API |
| **DWG Budget Intelligence** | Receives architectural DWG files via WhatsApp, analyzes with Autodesk APS + Claude Vision, returns structured budget data | APS · Claude · Next.js API |
| **Email Campaign Engine** | Multi-tenant transactional + campaign email system with per-client Resend isolation and 2,000+ contact base | Resend · Supabase · Next.js |

---

## Stack

#### Core
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

#### AI & Automation
![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

#### Infrastructure & Data
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

#### Integrations
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat-square&logo=resend&logoColor=white)
![Autodesk](https://img.shields.io/badge/Autodesk_APS-0696D7?style=flat-square&logo=autodesk&logoColor=white)

---

## How I think about systems

Most automation fails because it's built around the happy path. Real business processes have edge cases, retries, race conditions, and humans who don't follow instructions.

I design for that. Every agent I build has explicit failure handling, fallback logic, and observability. Every integration has a rollback plan. Multi-tenant means one client's data never touches another — enforced at the database level with Row Level Security, not just in application code.

The goal isn't to automate a task. It's to make the task disappear.

---

## Numbers that matter

- **59+ n8n workflows** in production across multiple clients
- **100,100+ contacts** managed and segmented in production CRM
- **< 5 seconds** opt-out processing time (LGPD compliance)
- **Multi-tenant** — single deployment serving isolated client environments
- **WhatsApp AI agents** handling inbound sales conversations 24/7

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/marciopaulo)
[![Website](https://img.shields.io/badge/voxsolutions.tech-1a5c2a?style=flat-square&logo=google-chrome&logoColor=white)](https://voxsolutions.tech)
[![Email](https://img.shields.io/badge/contato@voxsolutions.tech-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:contato@voxsolutions.tech)
