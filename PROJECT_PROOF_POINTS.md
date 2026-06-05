# Project Proof Points

Last updated: 2026-06-05
Status: Active / Evidence-backed summary

## Purpose

This file keeps the focus on concrete project work.

The proof-of-work compiler, source indexes, and weekly review process are documented as a real part of the operating model. They are important secondary proof points, but the main evidence is the product and execution work behind job-agent, PKM, and the household budget app.

## Project Portfolio

| Project | Current Role | Evidence Status | Recruiter Relevance |
|---|---|---|---|
| Job-agent / job-agent UX | Primary proof point: career workflow product with CV, job discovery, application support, privacy, feedback, QA, deployment, telemetry, billing planning, personal-context mining, and future inline AI editing | Verified / Internal; source commits inspected through 2026-06-05 plus local project summaries | Shows full-stack product execution, career-domain judgment, privacy-aware design, test discipline, and AI-assisted workflow design |
| PKM | Supporting proof point: personal knowledge-management product with ingestion, search, learning, social/feed, browser extension, backend/frontend structure, and feature lifecycle workflow | Internal / Verified; no new commits found in 2026-06-01 to 2026-06-05 connector scan | Shows information architecture, knowledge workflows, ingestion thinking, and project prioritization |
| Household budget app | Supporting proof point: Swedish household budgeting app with shared household, imports, transaction review, forecasting, goals, RLS/security, and extensive unit-test surface | Internal / Verified; no new commits found in 2026-06-01 to 2026-06-05 connector scan | Shows domain modeling, financial-product UX, privacy/security thinking, and test-backed product development |

## Case Study Links

| Project | Case Study |
|---|---|
| Job-agent / job-agent UX | [case-studies/JOB_AGENT_CASE_STUDY.md](case-studies/JOB_AGENT_CASE_STUDY.md) |
| PKM | [case-studies/PKM_CASE_STUDY.md](case-studies/PKM_CASE_STUDY.md) |
| Household budget app | [case-studies/HOUSEHOLD_BUDGET_CASE_STUDY.md](case-studies/HOUSEHOLD_BUDGET_CASE_STUDY.md) |

## Current Status Link

For the current portfolio status snapshot, see [PROJECT_STATUS.md](PROJECT_STATUS.md).

## Primary Narrative

The strongest story is:

> I use AI-native workflows to design, build, test, document, and improve real products. The portfolio evidence layer shows how that work is captured, reviewed, and translated into recruiter-readable evidence without exposing private project material.

## Job-Agent Proof Points

| Area | Evidence Summary | Status |
|---|---|---|
| Product scope | Career workflow product covering CV pipeline, job discovery, application assistant, interview/practice flows, feedback, privacy, settings/billing surfaces, and career-context reuse | Verified / Internal |
| Personal-context mining | Source commits add document batch upload support, preview-first extraction, source-attributed mined facts, snippet/persona/experience mirroring, sensitive-data and duplicate handling, request-size limits, and CV prompt integration | Verified: `3b155e3`, `0b7a66e`, `c6f4afc`, `891f821` |
| Execution system | Career-ops tasks separate architecture decisions, implementation instructions, acceptance checklists, validation steps, ops runs, and repo-state reconciliation | Internal / Verified |
| QA discipline | Backend tests, Playwright coverage, live frontend/backend verification notes, CI workflow references, and regression-focused docs are present in the source material; latest head had Vercel success but no GitHub workflow runs returned in this connector pass | Verified / Needs Review for full test-suite status |
| Privacy and trust | GDPR/cookie consent, data-rights models, retention/anonymization planning, marketing-pixel guardrails, legal-review blockers, sensitive-data warnings, and bounded context-mining inputs are tracked | Internal / Verified |
| Product judgment | Open decisions include token pricing, referral economy, deployment activation, observability, Stripe live activation, destructive data-rights workflows, and next inline AI rewrite editor scope | Internal / Verified |
| Reproducible handoff | The source repo has a recruiter-safe install and LLM handoff layer checked against env examples, compose, Makefile, package metadata, requirements, migrations, current-status docs, and repo-ops startup/LLM handoff files | Verified |
| Static demo portal | Recruiter-safe static click-through is published publicly from a separate demo repo, with job-agent company research as the strongest surface and explicit public-source/synthetic/inferred-demo labels | Verified |

## Current Project Status Summary

| Project | Current State | Open Work |
|---|---|---|
| Job-agent | Local status marks the MVP complete and career-ops tasks done; privacy, feedback, QA, discovery, shared-job cleanup, CI, telemetry, billing, deployment planning, OAuth/social-auth landing, nav integration, startup/LLM handoff docs, repo-ops handoff refreshes, personal-context mining, and inline rewrite editor planning are represented | Production activation, legal review, live Stripe, public backend origin, observability setup, public-safe evidence excerpts, workflow/test verification beyond Vercel status, and branch/repo-ops cleanup |
| PKM | Knowledge-workflow product with ingestion/search/learning/feed/source/person/topic surfaces, feature lifecycle discipline, a Chrome extension for browser capture, and a 2026-05-26 frontend dependency-maintenance commit | OpenAI billing/quota, SMTP, deployment, source/person/topic setup, and verification of search, flashcard, extension, and MCP paths |
| Household budget app | Core budgeting surfaces plus substantial household/shared-account hardening, invite onboarding, ownership rules, read-model/view-model extraction, mutation helper consolidation, and a 2026-05-26 app dependency-maintenance commit | Finish post-hardening migration cleanup, remove legacy bridge debt, validate Supabase ownership hardening, and split future modeling into smaller slices |

## Supporting Project Signals

### PKM

- Uses feature queues, brainstorm queues, ICE scoring, and explicit lifecycle states.
- Contains backend/frontend structure, ingestion routes, search, embeddings, learning routes, feed/social tests, and a browser extension.
- Social feed work is marked `done` in the local feature queue, while full daily-use readiness still depends on operational setup and verification.
- Latest observed repo signal is dependency maintenance on 2026-05-26; do not present it as product-outcome validation.
- No new PKM commits surfaced in the 2026-06-01 to 2026-06-05 connector scan.
- Demonstrates knowledge workflow design rather than generic note-taking.

### Household Budget App

- Defines a desktop-first Swedish household budgeting product with shared household, imports, review queues, liquidity forecasting, goals, credit-card handling, and category/rule logic.
- Maintains durable product memory, roadmap/status docs, handoff docs, and a broad test surface.
- Recent status emphasizes household-scoped reads/writes, shared-account ownership hardening, invite onboarding, and moving complex page logic into dedicated read models, view models, workflow helpers, and mutation helpers.
- Latest observed repo signal is dependency maintenance on 2026-05-26; do not present it as product-outcome validation.
- No budget-app commits surfaced in the 2026-06-01 to 2026-06-05 connector scan.
- Demonstrates careful domain modeling and security-aware household data access.

## How The Automation Fits

The compiler and source-indexing workflow should stay documented because they show method, repeatability, and operating discipline. They should be described as:

- documented automation infrastructure
- evidence extraction
- weekly review
- recruiter translation layer
- privacy and claim-quality control

They should be positioned as secondary proof points unless the specific document is about the portfolio evidence layer or automation system itself.

## Evidence Boundaries

- Recruiter-facing documents should not expose private local paths.
- Raw chat logs and project internals should be summarized, not copied.
- Exact metrics should only be used when verified.
- Internal project status can be cited as `Internal / Verified` when grounded in indexed local files, but recruiter-facing files should link to summaries rather than local-only index files.
- 2026-06-05 source-repo claims are limited to GitHub commit metadata/diffs and status checks inspected through the connector.
