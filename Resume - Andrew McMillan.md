# Andrew McMillan

Kelowna, BC · andrew@andamonium.dev · andamonium.dev · github.com/andrewrmcmillan · github.com/ItsAndrewM

## SUMMARY

Senior full-stack engineer who ships products end-to-end and builds on Cloudflare's developer platform: Workers, Durable Objects, Workers AI, and the Agents SDK. Builds agentic tools, including two code review services, where application code validates what the model proposes and holds the verdict, backed by lint rules, hooks, and benchmarks.

## TECHNICAL SKILLS

**Languages:** TypeScript, JavaScript, Go, Python, SQL, HTML/CSS

**Cloudflare:** Workers, Durable Objects (SQLite), Workers AI, Agents SDK, Containers, Queues, Workflows, D1, R2, Access

**AI Engineering:** Claude, Workers AI models, GPT-4o, MCP servers, structured output with schema validation, recall benchmarks, replay evaluation, spend caps, Claude Code skills and hooks, custom oxlint rules

**Product Engineering:** React 19, Next.js, TanStack, Tailwind CSS, Capacitor, Hono, Node.js, REST/OpenAPI, GraphQL

**Data & Cloud:** PostgreSQL, Redis, Firestore, MySQL/MariaDB, Stripe, GCP Cloud Run, Terraform, GitHub Actions, Playwright, Vitest

## WORK EXPERIENCE

**Senior Software Engineer, GameSheet Inc.** · Newmarket, ON, remote | **2024 - Present**

- Own the embeddable stats widget end-to-end: a Next.js App Router and React 19 product with a dedicated BFF that serves live scores, standings, and player statistics on league websites across North America. Authored 95% of its commits and replaced the prior product behind existing public URLs with no embedder changes.
- Built Project Warden, a code review service on Cloudflare Workers and Durable Objects that runs before a pull request is opened, now in pilot. An author or coding agent uploads a commit, Claude reviews it, and each later round reviews only what changed. Application code decides readiness and caps spend at $2 a review. Ships as a CLI and a three-tool MCP server.
- Wrote the team's oxlint plugin (seven rules, used in 6 repositories), set up a Copilot review status check in 16 repositories, and wrote most of the shared Claude Code skills for deploys, triage, and merges, plus hooks that lint an agent's edits and send it back to fix errors before it finishes.
- Built gamesheet-bot, an agentic GitHub PR reviewer packaged for Cloud Run: Zod-validated reports, a verdict computed by application code, a no-post replay harness against real PRs, and secret allowlisting and redaction for untrusted code.
- Lead development of the Teams+ monorepo, contributing about 70% of 3,000 commits across a React 19 and Capacitor app for web, iOS, and Android, a Hono API gateway on Cloud Run, and a shared Storybook design system.
- Built an event-driven Firebase Auth to PostgreSQL identity bridge and a batch reconciler that repairs historical account mismatches.
- Restored live scoring after a mis-scoped Redis credential caused an outage, rolled back within the hour, and replayed events to recover all 159 affected games.
- Work across a 1,000-file Terraform estate covering Cloud Run services, DNS, secrets management, and VCS-driven infrastructure delivery.

**Founder and Sole Engineer, PlayLabs** · Kelowna, BC | **2024 - Present**

- Built and launched a live AI SaaS for K-5 physical-education teachers; the production build took 3.5 weeks and 115 commits, and it is now in pilot with teachers.
- Own all three production surfaces: a React 19 SPA, an OpenAPI Hono API on Cloudflare Workers, and a Next.js marketing site.
- Designed the AI features on GPT-4o: curriculum-aligned lesson generation, a durable Cloudflare Workflow that builds a 20-lesson semester, and content moderation tuned for K-5.
- Built the Supabase PostgreSQL data model through 40 migrations with row-level security, and Stripe subscriptions across three tiers with per-tier AI limits.

**Software Engineer, Precision Sail Loft Ltd.** · Sidney, BC | **2023 - 2024**

- Owned full-stack changes across three marine e-commerce sites, including WordPress and WooCommerce systems in PHP and JavaScript and a Next.js storefront integrated with WooCommerce operations.
- Redesigned MySQL and MariaDB schemas, shipped custom product tools and plugins, and instrumented performance and conversion tracking with Google Analytics, Search Console, and Tag Manager.

**Freelance Full-Stack Developer, dinocode** · Kelowna, BC | **January 2023 - Present**

- Run a freelance practice delivering e-commerce, marketing sites, and dashboards for small businesses, owning discovery, design, development, integrations, deployment, and client communication.
- Built and maintain a Next.js 16 farm storefront and API backed by Square, keeping its online catalog and inventory aligned with the existing physical point-of-sale system.

## PROJECTS

**andabot** | **2026** · Self-hosted pull request reviewer on Cloudflare Workers, Durable Objects, Workers AI, and the Agents SDK. Host code validates every finding against the diff and derives the verdict, and changes are judged on a frozen 22-pull-request recall benchmark. 560 commits, 2,081 tests.

**Baby tracker** | **2026** · Two-caregiver tracker in daily use, on one SQLite Durable Object behind Cloudflare Access, with a 100% domain coverage gate, tests under two time zones, and migrations rehearsed against real exports.

**Strix** | **2026, in progress** · Hockey video event tagger: an ffmpeg container slices games, a Queue fans clips out to a Workers AI multimodal model, and code validates the typed answers and applies confidence thresholds.

## EDUCATION

**Concordia University, Montreal** | **December 2022**

Diploma, Fullstack Web Development

**Camosun College, Victoria** | **June 2017**

B.A. Sport and Fitness Leadership, With Distinction · Diploma, Sport Management · Certificate, Business Management
