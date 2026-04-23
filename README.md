# Austin Johnnic

**Founder · AI Engineer · Software Engineer**

austin_johnnic@sovyren.com · Naperville, IL
[linkedin.com/in/a-johnnic](https://linkedin.com/in/a-johnnic) · [github.com/austinj-dev](https://github.com/austinj-dev) · [sovyren.com](https://sovyren.com)
[agints.app](https://agints.app) · [agint.app](https://agint.app) · [tablework.io](https://tablework.io)

---

## Summary

Founder of Sovyren Inc., an R&D lab shipping production-grade AI, software, and automation systems. Sole architect and developer across three commercial product lines: a horizontal agentic OS, a proprietary AI model family served via REST API, and an integrated SMB operations suite. Designs and ships full-stack systems end-to-end — from PostgreSQL schema design and RLS policy engineering to LLM orchestration, MCP server development, and enterprise-grade multi-tenant architecture. Authored proprietary engineering methodologies covering systems planning, threat modeling, database architecture, CI/CD automation, and AI operations.

---

## Core Competencies

**AI Engineering & LLM Infrastructure** — Proprietary model family (Agint 1, 1o, 1o-mini) served via REST API; complexity-based model routing with automatic fallback chains and circuit breakers; token cost attribution; RAG pipelines with pgvector (HNSW indexing); 4-layer memory architectures (conversation / session / user / org); custom agent orchestration with 200+ tool registries; MCP server development.

**Agent Systems & Orchestration** — Multi-agent team coordination (Agint Crews); 6-layer system prompt assembly; real-time monitoring, audit, and cost control; visual agent builders with React Flow; voice assistants; industry-specific template orchestration; marketplace architecture with Stripe Connect and 70/30 revenue splits.

**Self-Hosted Backend Infrastructure** — Self-hosted Supabase on local Mac Pro hardware (Auth, Postgres, Storage, Edge Functions, Realtime); self-hosted Agint model inference on Vast.ai RTX 4090; self-hosted faster-whisper STT and Piper TTS; Cloudflare Workers for web layer. Infrastructure philosophy prioritizing self-hosting over managed services wherever operationally viable.

**Systems Architecture** — Multi-tenant SaaS at scale (900+ tables, org-scoped isolation); serverless-primary architecture (Cloudflare Workers, Supabase, Vercel); 4-layer permission cascades with 6-tier RBAC; subscription tier gating with feature flags; embeddable portal and widget architectures; JWT secret sync for cross-product SSO; Turborepo + pnpm monorepos; open-core architectures with published MCP server packages.

**Database Engineering** — PostgreSQL schema design at scale (340+ migrations, 2,100+ indexes, 1,600+ RLS policies); Row-Level Security policy engineering; pgvector for semantic search; Drizzle ORM; multi-database patterns across Supabase, Neon, MongoDB, Redis, PlanetScale, DynamoDB, ClickHouse, Neo4j, and Elasticsearch.

**Security & Quality** — STRIDE threat modeling; OWASP Top 10 2025; penetration test planning; WCAG 2.2 AA accessibility; incident response playbooks; HTTP security headers; 37-phase production readiness methodology; Playwright test automation.

**Full-Stack Development** — React 19, Next.js 15 (App Router + Turbopack), Astro 5, TypeScript (strict), Hono on Cloudflare Workers, Mantine v8, shadcn/ui, Tailwind CSS, TanStack Query, Zustand, Zod, React Flow, Tiptap, Vite, Supabase, Stripe Connect, Resend, Deno.

**AI-Assisted Development & Tooling** — Claude Code CLI (primary), Cursor, Codex, Gemini CLI, Qwen Code CLI, Claude Cowork, Claude Design, Google Stitch; authored proprietary Claude Code skill suites (engineering, QA, security, operations, growth); MCP server publishing to npm; CI/CD pipeline design; bash automation for forensic-grade rebrand operations across 900+ tables.

---

## Experience

### Founder & AI / Software Engineer — Sovyren Inc.
*2025 – Present · Naperville, IL*

Founded an R&D lab for applied AI and enterprise software. Sole architect and developer across three commercial product lines, responsible for systems architecture, database design, backend infrastructure, frontend development, AI systems, security posture, brand, and product strategy.

**Agints (agints.app) — Horizontal Agentic OS**

- Architected and built the Agints platform, consisting of **Colleagues** (business operations surface with unified chat) and **Studio** (visual + code + React Flow agent builder). Positioned as a horizontal enterprise agentic OS with persistent state, unified data layers, multi-tenancy, and granular access control.
- Designed the full agent runtime: 6-layer system prompt assembly, 4-layer memory (conversation / session / user / org), 200+ tool registry, MCP protocol for connectors, and Agint Crews for multi-agent team coordination.
- Built the Agent Command Center for real-time monitoring, audit trails, and cost tracking across deployed agents.
- Shipped the `@agint/cli` npm package (init, plan, team, skill, remote commands) for programmatic agent lifecycle management.
- Architected the agent marketplace with Stripe Connect integration and 70/30 revenue split for third-party builders.
- Implemented voice assistant with self-hosted faster-whisper STT and Piper TTS; notification threading as a team activity feed.
- Pricing: Free / $39 / $79 / Enterprise per seat.

**Agint Models (agint.app) — Proprietary AI Model Family**

- Designed and shipped the Agint model family (Agint 1, Agint 1o, Agint 1o-mini) available via REST API.
- Built a multi-provider AI gateway with self-hosted Agint models as primary inference and Claude API as fallback.
- Self-hosted inference on Vast.ai RTX 4090 infrastructure; fallback chains with circuit breakers.

**TableWork (tablework.io) — Integrated SMB Operations Suite**

- Designed and shipped the TableWork suite: **atlas** (CRM / SMB operations), **balance** (bookkeeping / finance), and **signal** (customer feedback, waitlist, changelog, NPS) — available standalone or bundled.
- Architected **tablework-auth** — a unified authentication layer providing shared identity across individual products and the suite bundle via JWT secret sync across product Supabase projects, enabling cross-subdomain SSO without auth-exchange handoffs.
- Built a unified dashboard at the bundle domain with Stripe bundle subscription tiers.
- Pricing: standalone products from ~$8–9/mo; bundle tiers $19–$79/mo.

**Cross-Platform Engineering**

- Authored the **Applied Engineering** methodology — a 9-stage systems planning framework that produces 15–22 project documents (architecture specs, data models, security postures, deployment runbooks, API inventories, cost estimates, launch checklists) from structured requirements gathering across 25+ question categories. Supports Claude Code, Cursor, Windsurf, Lovable, Bolt, Replit Agent, and Codex.
- Authored the **QA Engineering** methodology — a two-mode (Discovery / Fix) testing framework with 37 dynamically-enabled phases covering OWASP Top 10 2025, WCAG 2.2 AA accessibility, STRIDE threat modeling, and production readiness verification.
- Authored the **Sovyren Labs** skill suite — modular AI-assisted development system across five domains with 20+ sub-skills: systems planning, multi-database patterns, CI/CD automation, STRIDE/OWASP audits, AI operations (model routing, cost tracking), branded document generation, product strategy, investor communications, and incident response.
- Executed full-scale repository rebrand across 900+ tables using automated bash scripts, a 52-question forensic questionnaire, and forensic verification of binary files, hidden configs, and third-party references. Resolved 3,000+ TypeScript errors; built production readiness testing with Playwright across 380+ pages.

---

## Open Source & Side Projects

**Applied Engineering Skill** *(Claude Code Skill — Open Source)*
9-stage systems planning methodology generating 15–22 project documents. 25+ question categories, 19 stack references, 23 document templates.

**QA Engineering Skill** *(Claude Code Skill — Open Source)*
37-phase production readiness methodology with two-mode (Discovery / Fix) architecture. Full OWASP Top 10 2025, WCAG 2.2 AA, STRIDE threat modeling, 25 checklists, 15 templates.

**Agint CLI** *(`@agint/cli` — npm)*
Command-line interface for the Agints platform with init, plan, team, skill, and remote subcommands for agent lifecycle management.

---

## Technical Environment

**Languages** — TypeScript, JavaScript, Python, SQL, Bash, Deno

**Frontend** — React 19, Next.js 15, Astro 5, Mantine v8, shadcn/ui, Tailwind CSS, TanStack Query, Zustand, Recharts, Tiptap, React Flow

**Backend** — Hono, Supabase, PostgreSQL, pgvector, Drizzle ORM, Stripe Connect, Resend, Cloudflare Workers, Vercel Serverless, Deno Edge Functions, Turborepo, pnpm

**AI / ML** — Self-hosted Agint model family, Anthropic Claude API, OpenAI API, Google Gemini, Groq, HuggingFace, Vercel AI SDK, RAG, pgvector embeddings, MCP protocol, custom agent orchestration, faster-whisper STT, Piper TTS

**Security & Quality** — STRIDE, OWASP Top 10 2025, RLS policy engineering, penetration test planning, WCAG 2.2 AA, Playwright

**Tools** — Claude Code CLI, Cursor, Codex, Gemini CLI, Qwen Code CLI, Claude Cowork, Claude Design, Google Stitch, Git, Docker, VS Code, Vast.ai

---

## Education

Self-directed engineering education through applied AI systems development, open-source contributions, and enterprise product architecture.
