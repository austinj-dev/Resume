# Austin Johnnic

**Founder · AI Engineer · Software Engineer**

austin_johnnic@sovyren.com · Naperville, IL
[linkedin.com/in/a-johnnic](https://linkedin.com/in/a-johnnic) · [github.com/austinj-dev](https://github.com/austinj-dev) · [sovyren.com](https://sovyren.com)
[agints.app](https://agints.app) · [agint.app](https://agint.app) · [tablework.io](https://tablework.io)

---

## Summary

Founder of Sovyren LLC, an R&D lab shipping production-grade AI, software, and automation systems. Sole architect and developer across three commercial product lines: a horizontal agentic OS, a proprietary AI model family served via REST API, and a unified, modular SMB operations platform. Designs and ships full-stack systems end-to-end — from PostgreSQL schema design and RLS policy engineering to LLM orchestration, MCP server development, and enterprise-grade multi-tenant architecture. Authored proprietary engineering methodologies covering systems planning, threat modeling, database architecture, CI/CD automation, and AI operations.

---

## Core Competencies

**AI Engineering & LLM Infrastructure** — Proprietary model family (Agint 1, 1o, 1o-mini) served via REST API; complexity-based model routing with automatic fallback chains and circuit breakers; token cost attribution; RAG pipelines with pgvector (HNSW indexing); 4-layer memory architectures (conversation / session / user / org); custom agent orchestration with 200+ tool registries; MCP server development.

**Agent Systems & Orchestration** — Multi-agent team coordination (Agint Crews); 6-layer system prompt assembly; real-time monitoring, audit, and cost control; visual agent builders with React Flow; voice assistants; industry-specific template orchestration; marketplace architecture with Stripe Connect and 70/30 revenue splits.

**Self-Hosted Backend Infrastructure** — Self-hosted Supabase on local Mac Pro hardware (Auth, Postgres, Storage, Edge Functions, Realtime); self-hosted Agint model inference on Vast.ai RTX 4090; self-hosted faster-whisper STT and Piper TTS; Cloudflare Workers for web layer; Cloudflare Tunnel and R2 for public access and object storage; self-hosting prioritized over managed services wherever operationally viable.

**Systems Architecture** — Multi-tenant SaaS at scale (900+ tables, org-scoped isolation); serverless-primary architecture (Cloudflare Workers, Supabase, Vercel); 4-layer permission cascades with 6-tier RBAC; subscription tier gating with feature flags; a three-mode adaptive interaction shell (chat-inline / split / full dashboard) shared across products; embeddable portal and widget architectures; cross-product SSO via signed JWTs with key rotation; Turborepo + pnpm monorepos; open-core MCP packages.

**Database Engineering** — PostgreSQL schema design at scale (340+ migrations, 2,100+ indexes, 1,600+ RLS policies); schema-isolated multi-product databases with reusable membership/role policy helpers; Row-Level Security engineering; pgvector semantic search; Drizzle ORM; multi-database patterns across Supabase, Neon, MongoDB, Redis, PlanetScale, DynamoDB, ClickHouse, Neo4j, and Elasticsearch.

**Security & Quality** — STRIDE threat modeling; OWASP Top 10 2025; penetration test planning; WCAG 2.2 AA accessibility; incident response playbooks; HTTP security headers; 37-phase production readiness methodology; Playwright test automation.

**Full-Stack Development** — React 19, Next.js 15 (App Router + Turbopack), Astro 5, TypeScript (strict), Hono on Cloudflare Workers, shadcn/ui, Radix UI, Tailwind CSS, TanStack Query, Zustand, Zod, React Flow, Tiptap, Vite, Supabase, Stripe Connect, Resend, Deno.

**AI-Assisted Development & Tooling** — Claude Code CLI (primary), Cursor, Codex, Gemini CLI, Qwen Code CLI, Claude Cowork, Claude Design, Google Stitch; authored proprietary Claude Code skill suites (engineering, QA, security, operations, growth); MCP server publishing to npm; CI/CD pipeline design; multi-agent build orchestration across parallel tmux sessions; bash automation for forensic-grade rebrand operations across 900+ tables.

---

## Experience

### Founder & AI / Software Engineer — Sovyren LLC
**2025 – Present · Naperville, IL**

Founded an R&D lab for applied AI and enterprise software. Sole architect and developer across three commercial product lines, responsible for systems architecture, database design, backend infrastructure, frontend development, AI systems, security posture, brand, and product strategy.

#### Agints ([agints.app](https://agints.app)) — Horizontal Agentic OS

- Architected and built the Agints platform, consisting of Colleagues (business operations surface with unified chat) and Studio (visual + code + React Flow agent builder). Positioned as a horizontal enterprise agentic OS with persistent state, unified data layers, multi-tenancy, and granular access control.
- Designed the Adaptive Chrome interaction model — a chat-first, three-mode shell where the AI renders module data as inline artifacts (Mode 1), opens a split-view contextual ops center alongside chat (Mode 2), or expands to a full traditional dashboard with a floating chat launcher (Mode 3) — all rendering the same data under one entitlement model.
- Designed the full agent runtime: 6-layer system prompt assembly, 4-layer memory (conversation / session / user / org), 200+ tool registry, MCP protocol for connectors, and Agint Crews for multi-agent team coordination.
- Built the Agent Command Center for real-time monitoring, audit trails, and cost tracking across deployed agents.
- Shipped the `@agint/cli` npm package (init, plan, team, skill, remote commands) for programmatic agent lifecycle management.
- Architected the agent marketplace with Stripe Connect integration and 70/30 revenue split for third-party builders.
- Implemented voice assistant with self-hosted faster-whisper STT and Piper TTS; notification threading as a team activity feed.
- Pricing: Free / $39 / $79 / Enterprise per seat.

#### Agint Models ([agint.app](https://agint.app)) — Proprietary AI Model Family

- Designed and shipped the Agint model family (Agint 1, Agint 1o, Agint 1o-mini) available via REST API.
- Built a multi-provider AI gateway with self-hosted Agint models as primary inference and a Claude → Gemini fallback chain.
- Self-hosted inference on Vast.ai RTX 4090 infrastructure; fallback chains with circuit breakers.

#### TableWork ([tablework.io](https://tablework.io)) — Unified, Modular SMB Operations Platform

- Architected and built TableWork as a single, unified platform composing three modules over one shared backbone — Atlas (field operations: scheduling, dispatch, routes, jobs, contacts), Balance (finance: invoicing, payments, bank reconciliation, journal entries), and Signal (customer-facing: feedback, changelog, public roadmap, NPS) — available individually or as a bundle.
- Built the same three-mode adaptive interaction shell as Agints (Generative / Split / Traditional), with a chat-first surface aware of all three modules and a contextually filtered sidebar that follows the active module.
- Designed a single multi-tenant PostgreSQL database with schema-level isolation across platform, billing, AI, comms, marketplace, analytics, audit, and per-module schemas; org-scoped Row-Level Security enforced through reusable membership and role-check policy helpers.
- Engineered unified cross-product identity with ES256-signed JWTs and JWKS-based key rotation, replacing the prior shared-secret model; self-hosted Supabase stack on Mac Pro hardware with digest-pinned containers and Cloudflare Tunnel public access.
- Backed the AI surface with the Agint model gateway (self-hosted vLLM primary, Claude / Gemini fallback chain).
- Plans: Solo / Pro / Business / Scale / Enterprise.

#### Cross-Platform Engineering

- Authored the Applied Engineering methodology — a 9-stage systems planning framework that produces 15–22 project documents (architecture specs, data models, security postures, deployment runbooks, API inventories, cost estimates, launch checklists) from structured requirements gathering across 25+ question categories. Supports Claude Code, Cursor, Windsurf, Lovable, Bolt, Replit Agent, and Codex.
- Authored the QA Engineering methodology — a two-mode (Discovery / Fix) testing framework with 37 dynamically-enabled phases covering OWASP Top 10 2025, WCAG 2.2 AA accessibility, STRIDE threat modeling, and production readiness verification.
- Authored the Sovyren Labs skill suite — modular AI-assisted development system across five domains with 20+ sub-skills: systems planning, multi-database patterns, CI/CD automation, STRIDE/OWASP audits, AI operations (model routing, cost tracking), branded document generation, product strategy, investor communications, and incident response.
- Orchestrated multi-team, multi-agent platform builds across parallel Claude Code sessions in tmux, enforcing phase gates, integration discipline, and production-grade output (zero mocks, placeholders, or deferred features).
- Executed full-scale repository rebrand across 900+ tables using automated bash scripts, a 52-question forensic questionnaire, and forensic verification of binary files, hidden configs, and third-party references. Resolved 3,000+ TypeScript errors; built production readiness testing with Playwright across 380+ pages.

---

## Open Source & Side Projects

**Applied Engineering Skill** *(Claude Code Skill — Open Source)*
9-stage systems planning methodology generating 15–22 project documents; 25+ question categories, 19 stack references, 23 templates.

**QA Engineering Skill** *(Claude Code Skill — Open Source)*
37-phase production readiness methodology (Discovery / Fix); OWASP Top 10 2025, WCAG 2.2 AA, STRIDE, 25 checklists, 15 templates.

**Marquee** *(Claude Code Skill)*
Autonomous cinematic studio producing production-grade product and brand films end to end — script, voiceover, music, SFX, Remotion motion graphics, animated UI mockups, and rendered multi-aspect cuts (16:9 / 9:16 / 1:1) from a single brand intake.

**Agint CLI** *(`@agint/cli` — npm)*
Command-line interface for the Agints platform with init, plan, team, skill, and remote subcommands for agent lifecycle management.

---

## Technical Environment

**Languages** — TypeScript, JavaScript, Python, SQL, Bash, Deno

**Frontend** — React 19, Next.js 15, Astro 5, shadcn/ui, Radix UI, Tailwind CSS, TanStack Query, Zustand, Recharts, Tiptap, React Flow

**Backend** — Hono, Supabase, PostgreSQL, pgvector, Drizzle ORM, Stripe Connect, Resend, Cloudflare Workers, Cloudflare Tunnel, R2, Vercel Serverless, Deno Edge Functions, Turborepo, pnpm

**AI / ML** — Self-hosted Agint family, Claude API, OpenAI, Google Gemini, Groq, HuggingFace, Vercel AI SDK, vLLM, RAG, pgvector embeddings, MCP, agent orchestration, faster-whisper STT, Piper TTS

**Security & Quality** — STRIDE, OWASP Top 10 2025, RLS policy engineering, penetration test planning, WCAG 2.2 AA, Playwright

**Tools** — Claude Code CLI, Cursor, Codex, Gemini CLI, Qwen Code CLI, Cowork, Claude Design, Google Stitch, Git, Docker, VS Code, tmux

---

## Education

Self-directed — applied AI systems development, open-source contributions, and enterprise product architecture.
