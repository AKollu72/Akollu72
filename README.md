# Amrutha Kollu

**Software Engineer** · Bay Area, CA  
[LinkedIn](https://linkedin.com/in/amrutha-kollu) · kolluamrutha@gmail.com

---

I build tooling and infrastructure that makes frontend engineering faster
and more reliable. Currently at Socratics.ai, an AI-driven financial
modeling platform in the Bay Area.

## Fixel — Figma-to-React pipeline with continuous verification

[![npm](https://img.shields.io/npm/v/fixel)](https://www.npmjs.com/package/fixel)
[![downloads](https://img.shields.io/npm/dw/fixel)](https://www.npmjs.com/package/fixel)

**[github.com/AKollu72/fixel](https://github.com/AKollu72/fixel)** · built independently, live on npm

LLMs generate design values that are close-but-not-exact — a border radius
one step off the scale, a raw hex instead of the semantic token. Nothing
crashes; it's quietly wrong. Fixel fixes this architecturally:

1. **Deterministic resolution before generation** — color, spacing,
   typography, radius resolved algorithmically from Figma node data; the
   model never guesses at values with definitive answers
2. **Constrained generation** — the LLM handles structure and composition only
3. **Prohibited-pattern enforcement** — raw hex, wrong radius scales, and
   missing imports abort generation before any file is written
4. **Continuous CI verification** — every PR re-checks the committed spec;
   drift blocks the merge and posts back onto the Figma canvas as anchored
   comments, where designers actually work

### Auth0 enterprise migration

Full SPA to Regular Web App migration across 3 deployment environments.
OAuth 2.0 flows, multi-tenant configuration, session management.
Diagnosed a production auth failure in the orchestration environment
that two engineers before me could not resolve.

### AI-assisted codebase refactor

Part of the team that reduced a 100,000-line frontend to 40,000 lines
while maintaining product stability. Daily workflow involves directing
Cursor and Claude to implement features and debug issues, then reviewing
and fixing what they produce.

### Complex async debugging

Stale closures inside polling intervals, race conditions between Redux
thunks, MUI DataGrid infinite render loops, Hasura webhook sync failures.
Root cause is usually three layers deeper than the symptom.

## Day job

Software engineer at an AI-powered financial modeling platform. Shipped 60+
React components with 3,077 automated tests in 35 days. Led an Auth0
enterprise migration (SPA → Regular Web App, three environments, OAuth 2.0,
multi-tenant) and resolved a production auth failure two engineers before me
couldn't. Debugging specialty: the root cause is usually three layers deeper
than the symptom.

## Stack

```
Frontend     React · TypeScript · Next.js · Redux · MUI · Storybook · Chromatic
Backend      Node.js · Hasura (GraphQL) · REST APIs · Express
Auth         Auth0 · OAuth 2.0 · JWT · Multi-tenant config
Tooling      ts-morph · ESLint (custom rules) · fast-glob · Figma API
AI           Cursor · Claude Code · Codex· LLM-integrated pipelines
```
## Writing
[How We Shipped 60 Design System Components in 5 Weeks](https://dev.to/akollu72/how-we-shipped-60-design-system-components-in-5-weeks-using-figma-as-the-single-source-of-truth-1lkc)

[Why AI Keeps Generating the Wrong Design Tokens](https://dev.to/akollu72/why-ai-keeps-generating-the-wrong-design-tokens-and-how-i-fixed-it-with-figmas-api-17o4)

## Connect

[LinkedIn](https://linkedin.com/in/amrutha-kollu) · kolluamrutha@gmail.com
