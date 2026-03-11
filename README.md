# Austin Johnnic

**AI Systems Engineer**

austin_johnnic@sovyren.com | 51 Elmwood Dr, Naperville, IL 60540 | [linkedin.com/in/a-johnnic](https://linkedin.com/in/a-johnnic)

[github.com/austinj-dev](https://github.com/austinj-dev) | [sovyren.com](https://sovyren.com) | [usevera.cloud](https://usevera.cloud) | [useessentials.cloud](https://useessentials.cloud)

---

## Professional Summary

AI systems engineer and founder of **Sovyren Inc.**, building enterprise-grade software at the intersection of systems architecture, applied AI, and large-scale automation. Designed and shipped multi-tenant SaaS platforms with 920+ database tables, 1,600+ security policies, and multi-provider AI infrastructure with model routing, fallback chains, and RAG pipelines. Authored production engineering methodologies spanning systems planning, threat modeling, database architecture, CI/CD automation, and AI operations — adopted across open-source and enterprise contexts. Deep hands-on experience across the full stack: from PostgreSQL schema design and RLS policy engineering to LLM orchestration, agent architectures, and MCP server development.

---

## Core Competencies

**AI Engineering & LLM Infrastructure:** Multi-provider AI orchestration (Anthropic, OpenAI, Google, Groq, HuggingFace), model routing and complexity-based selection, automatic fallback chains with circuit breakers, BYOK key management, token cost tracking and attribution, prompt versioning systems, RAG pipelines with pgvector (HNSW indexing), 4-layer memory architectures, custom agent orchestration with tool registries, MCP server development

**Systems Architecture & Infrastructure:** Multi-tenant SaaS design (920+ tables, org-scoped isolation), serverless-primary architecture (Vercel + Supabase PostgREST + Realtime), 4-layer permission cascades, RBAC with 6-tier hierarchy, subscription tier gating with feature flags, embeddable portal/widget architectures, industry-specific configuration systems ("lens filters"), audit trail engineering

**Database Engineering:** PostgreSQL schema design at scale (341 migrations, 2,179 indexes, 1,607 RLS policies), Row-Level Security policy engineering, pgvector for semantic search, multi-database patterns (Supabase, Neon, MongoDB, Redis, PlanetScale, DynamoDB, ClickHouse, Neo4j, Elasticsearch), migration strategy, query optimization

**Security & Quality Engineering:** STRIDE threat modeling, OWASP Top 10 2025 assessment, penetration test planning, WCAG 2.2 AA accessibility, incident response playbooks, HTTP security headers, production readiness verification (37-phase methodology), Playwright test automation

**Full-Stack Development:** React 18, Next.js 15 (App Router + Turbopack), TypeScript (strict), Mantine v8, shadcn/ui, Tailwind CSS, TanStack Query, Zustand, Zod, ReactFlow, Tiptap, Vite, Supabase (Auth, Postgres, Storage, Edge Functions, Realtime), Stripe, Resend, Deno, Cloudflare Workers, Vercel serverless

**AI-Assisted Development & Tooling:** Claude Code, Codex, Cursor, Lovable, Bolt, Replit Agent — systems-level prompt engineering for architecting and executing complex implementations, custom Claude Code skill authoring (engineering, QA, security, operations, growth), MCP server development, CI/CD pipeline design, bash automation

---

## Experience

### Founder & AI Systems Engineer — Sovyren Inc.
**2025 – Present** | Naperville, IL

- Founded an R&D lab for applied AI and enterprise software. Sole architect and developer of a portfolio of SaaS products — responsible for systems architecture, database design, backend infrastructure, frontend development, AI systems, security posture, and product strategy.

- Architected and built **Vera OS**, an enterprise multi-tenant operations platform (CRM, Sales, Project Management, Support, HR, Finance, Property Management) with an industry-specific pack system and 6 external portal types. **652 pages** (Next.js App Router), **26 modules**, **12 industry packs**, **277 UI components**, **167 custom hooks**, and 8 Zustand stores.

- Designed the Vera OS database layer: **920+ tables** across 25+ domain prefixes, **1,607 RLS policies** enforcing multi-tenant data isolation at the database layer, **2,179 indexes**, **341 migration files**, soft deletes, JSONB metadata columns, and a full audit trail. Supabase PostgREST auto-API eliminates boilerplate CRUD functions.

- Engineered a 4-layer permission cascade (Subscription Tier → Platform override → Org override → Final) with RBAC enforced at both application and database layers. Built an industry pack "lens filter" system that transforms terminology, navigation, columns, tabs, and routes per industry without altering the core module structure.

- Built 27 serverless API routes covering Stripe payments/subscriptions/webhooks, OAuth integrations (QuickBooks, Xero), AI chat and text transformation, cron jobs (invoice reminders, daily digest, task reminders, cleanup), GDPR data export, and industry pack snapshot export/import. PWA with service worker and offline queue.

- Designed **Vera AI**, an autonomous enterprise intelligence platform: 4-layer memory system (conversation, user memory, RAG knowledge base, business context), 6 agent modes (Chat, Operator, Research, Build, Automation, Advisor), custom TypeScript agent orchestration engine with tool registry, and a multi-provider AI gateway with complexity-based model routing and automatic fallback chains.

- Engineered **Essentials by Sovyren** with a Core + Workflow Packs architecture (Book, Schedule, Docs) at Starter and Pro tiers — 49 database tables with full Stripe integration for solopreneurs and small teams.

- Resolved 3,000+ TypeScript errors and built a production readiness testing system using Playwright across 388+ pages, covering CRUD operations, permission matrices, and cross-cutting edge cases.

- Authored the **Applied Engineering** methodology — a 9-stage systems planning framework that produces 15–22 project documents (architecture specs, data models, security postures, deployment runbooks, API inventories, cost estimates, launch checklists) from structured requirements gathering across 25+ question categories.

- Authored the **QA Engineering** methodology — a two-mode (Discovery/Fix) testing framework with 37 dynamically-enabled phases covering OWASP Top 10 2025, WCAG 2.2 AA accessibility, STRIDE threat modeling, and production readiness verification.

- Executed a full-scale repository rebrand across 920+ tables and all file types using automated bash scripts (debugging platform-specific detection issues), a 52-question forensic questionnaire, and comprehensive verification covering binary files, hidden configs, and third-party references.

- Designed the **Sovyren Labs** skill suite — a modular AI-assisted development system spanning 5 domains (engineering, quality, operations, growth, shared conventions) with 20+ sub-skills covering systems planning, multi-database patterns, CI/CD automation, STRIDE/OWASP security audits, branded document generation, product strategy, investor communications, tech evaluation, prompt management, model routing, and incident response.

- Defined product-line architecture across 13+ products spanning CRM, ERP, AI, media, field ops, commerce, talent, and developer tools — with clear separation between heavy operational platforms and standalone focused tools.

---

## Projects

**Applied Engineering Skill** *(Claude Code Skill)* — Open Source
9-stage systems planning methodology generating 15–22 project documents. 25+ question categories, 19 stack references, 23 document templates. Supports Claude Code, Cursor, Windsurf, Lovable, Bolt, Replit Agent, and Codex.

**QA Engineering Skill** *(Claude Code Skill)* — Open Source
37-phase production readiness methodology with two-mode (Discovery/Fix) architecture. Full OWASP Top 10 2025, WCAG 2.2 AA, STRIDE threat modeling, 25 checklists, 15 templates.

**Qwen Code Agents Toolpack** *(MCP Server)* — Open Source
Model Context Protocol server providing structured tool calling, file operations, and code execution capabilities for Qwen-based coding agents.

**Flow-Lens** *(MCP Server)* — Open Source
Model Context Protocol server for workflow analysis, visualization, and optimization.

**Sovyren Labs Skill Suite** *(AI Development System)* — Private Source
Modular skill system spanning 5 domains and 20+ sub-skills: systems planning, multi-database architecture (12 database technologies), security audits (STRIDE, OWASP), AI operations (model routing, cost tracking, BYOK, prompt management), CI/CD automation, branded document generation, product strategy, and incident response.

---

## Technical Environment

**Languages:** TypeScript, JavaScript, Python, SQL, Bash, Deno

**Frontend:** React 18, Next.js 15, Mantine v8, shadcn/ui, Tailwind CSS, TanStack Query, Zustand, Recharts, Tiptap, ReactFlow

**Backend:** Supabase, PostgreSQL, pgvector, Prisma, Stripe, Resend, Cloudflare Workers, Vercel Serverless, Deno Edge Functions

**AI / ML:** Anthropic Claude API, OpenAI API, Google Gemini, Groq, HuggingFace, Vercel AI SDK, RAG, Embeddings, MCP, Agent Orchestration

**Security:** STRIDE, OWASP Top 10, RLS Policy Engineering, Penetration Test Planning, WCAG 2.2 AA

**Tools:** Claude Code, Codex, Cursor, Lovable, Git, Playwright, Docker, VS Code, Remotion

---

## Education

*Self-directed engineering education through applied AI systems development, open-source contributions, and enterprise product architecture.*

---

sovyren.com | usevera.cloud | useessentials.cloud | github.com/austinj-dev
