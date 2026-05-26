# Amrutha Kollu

**Software Engineer** · Bay Area, CA  
[LinkedIn](https://linkedin.com/in/amrutha-kollu) · kolluamrutha@gmail.com

---

I build tooling and infrastructure that makes frontend engineering faster
and more reliable. Currently at Socratics.ai, an AI-driven financial
modeling platform in the Bay Area.

## What I've shipped

### Figment — Design system pipeline

A three-stage pipeline that makes Figma the literal source of truth
for React design systems.

**Stage 1:** Token reconnaissance. Fetches Figma fills for a target node,
compares against the existing token file, outputs a ready-to-paste patch
for missing tokens. One API call, thirty seconds.

**Stage 2:** Deterministic component generation. Every value with an exact
answer (typography variants, spacing, icon dimensions) is resolved
algorithmically before the generation model sees any data. Output is
scanned for prohibited patterns (raw hex values, incorrect border radii,
missing imports) and rejected if any are found.

**Stage 3:** Automated drift detection. `verify-figma` runs in CI on every
PR, fetching live Figma data and comparing it against the component source.
Pull requests that introduce drift do not merge.

**Results:** 60 components. 3,077 tests. Zero raw hex values. 35 business
days. Reduced per-component time from 4-5 engineer-days to less than 1 day.

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

## Connect

[LinkedIn](https://linkedin.com/in/amrutha-kollu) · kolluamrutha@gmail.com
