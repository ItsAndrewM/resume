# Andrew McMillan

Kelowna, BC · andrew@andamonium.dev · andamonium.dev · github.com/andrewrmcmillan · github.com/ItsAndrewM

## SUMMARY

Senior software engineer who ships products end-to-end — React frontends, TypeScript and Go APIs, and the cloud infrastructure beneath them. At GameSheet I build live sports-data products serving thousands of hockey rinks; after hours I run a freelance practice and a steady stream of side projects that make it to production.

## TECHNICAL SKILLS

**Languages:** TypeScript, JavaScript, Go, Python, SQL, HTML/CSS

**Frontend:** React 19, Next.js, TanStack (Router, Start, Query), Tailwind CSS, Capacitor, Storybook

**Backend:** Node.js, Hono, Express, REST/OpenAPI, GraphQL

**Data:** PostgreSQL, Redis, Firestore, MySQL/MariaDB, MongoDB

**Cloud & Infra:** GCP (Cloud Run, Cloud Functions, Pub/Sub), Cloudflare (Workers, R2, CDN), Firebase, Terraform, GitHub Actions, GitLab CI, AWS (S3, Lambda, SQS, DynamoDB)

**Testing:** Playwright, Vitest, Jest

**AI Engineering:** Claude Code (agentic workflows, MCP, custom skills), agent-assisted development across the SDLC

## WORK EXPERIENCE

**Senior Software Engineer,** GameSheet Inc. — Newmarket, ON (remote) | **2024 – Present**

- Own the embeddable stats widget end-to-end (Next.js App Router, React 19, dedicated BFF): live scores, standings, and player statistics embedded on league websites across North America — 95% of the codebase's commits, shipped as a drop-in replacement behind existing public URLs with zero embedder changes.
- Lead contributor to the team-management platform monorepo (~70% of 3,000 commits): a React 19 + Capacitor app shipping to web, iOS, and Android; a Hono API gateway on GCP Cloud Run; and a shared design system documented in Storybook.
- Built the identity bridge between Firebase Auth and Postgres: an event-driven provisioning function plus a batch reconciler that heals historical accounts, making dual-system consistency a guarantee instead of a chore.
- Own production incidents end-to-end: traced a live-scoring outage to a mis-scoped Redis credential, rolled back within the hour, then built an event-replay backfill that recovered all 159 affected games.
- Work across a 1,000-file Terraform estate (HCP Terraform Cloud, VCS-driven) covering Cloud Run services, DNS, and secrets management.
- Design and run edge services on Cloudflare Workers, including a public changelog API built with Hono and Zod, shipping a generated OpenAPI spec and interactive reference docs.
- Built the engineering team's agentic tooling: shared Claude Code skills that automate deploy tickets, release notes, and cross-team workflows against Jira and Slack.

**Software Engineer,** Precision Sail Loft Ltd. — Sidney, BC | **2023 – 2024**

- Engineered and maintained the company's WordPress/WooCommerce e-commerce platform (precisionsailloft.com) with PHP and JavaScript, plus sites for sister marine brands CDI Furlers and Inflatable Boat World.
- Built cdifurlers.com with Next.js as the full-stack framework, integrating WooCommerce for product management and back-office e-commerce.
- Redesigned MySQL and MariaDB schemas, materially improving query response times and data-retrieval efficiency.
- Shipped custom widgets, plugins, and Advanced Custom Fields integrations — including product-comparison tools for Inflatable Boat World.
- Instrumented sites with Google Analytics, Search Console, and Tag Manager for performance and conversion tracking.

**Freelance Full-Stack Developer,** dinocode — Kelowna, BC | **January 2023 – Present**

- Run a freelance development practice (dinocode.app) delivering full-stack builds for small businesses: e-commerce, marketing sites, and dashboards.
- Built and maintain shop.mcmillanfarms.ca for a working farm: a Next.js 16 frontend and API backed by Square, integrated with the farm's existing physical POS so online and in-store catalog and inventory stay in sync.
- Built mcmillanfarms.ca, the farm's public-facing site — a Next.js app built fully on React Server Components and SSR for fast, indexable seasonal content.
- Delivered sites for creative clients — the Tony Foster Band and the Oooh, Spooky podcast — owning design, build, and deployment end to end.

## PROJECTS

**andamonium.dev** | **2026** — Portfolio built on TanStack Start with full static prerendering, shadcn/Base UI, and native view transitions, deployed to Cloudflare Workers (in development).

**NLL Transactions Tracker** | **2023 – Present** — Scrapes, stores, and serves National Lacrosse League roster moves; TypeScript, React, Node.js, Postgres.

**GameSheet Contributions** | **2026** — Organization-wide Git contribution analytics: Cloudflare Worker BFF plus a React/Recharts dashboard, deployed on Cloudflare.

**PE+** | **2024 – Present** — Lesson-planning app for physical educators; React and Firebase, built with (and battle-tested by) real teachers.

## EDUCATION

**Concordia University, Montreal** | **December 2022**

Diploma, Fullstack Web Development

**Camosun College, Victoria** | **June 2017**

B.A. Sport and Fitness Leadership, With Distinction · Diploma, Sport Management · Certificate, Business Management
