<h1 align="center">Lumen</h1>

<p align="center"><strong>Analytics that explain themselves.</strong></p>

<p align="center">
  <em>The AI-native analytics platform for teams without a data team.</em>
</p>

---

## What we're building

Lumen is a **multi-tenant analytics platform** with AI at its core. Teams connect their data sources, ask questions in plain English, and get charts paired with AI-written narratives — no SQL, no dashboards to maintain.

- **Natural-language Q&A** over your data, powered by Anthropic Claude
- **Self-explaining charts** — every visualization ships with a written insight
- **Per-workspace AI budgets** — token limits, usage caps, full audit trail
- **Multi-tenant from day one** — built for SaaS, not retrofitted

## How it's built

Lumen ships as two services:

| Repo | Stack | Role |
|---|---|---|
| **lumen-web** | HTML · CSS · vanilla JS | Marketing site, product UI, admin panel |
| **lumen-api** | Python · FastAPI · MySQL · pandas | JSON API, auth, AI orchestration |

Both repos are private during pre-launch. Reach out if you'd like access.

## Tech we lean on

`Python` · `FastAPI` · `MySQL` · `pandas` · `bcrypt` · `JWT` · `Anthropic Claude` · `Vanilla JS` · `HTML/CSS`

## Currently focused on

- A production-ready MySQL schema with full multi-tenancy primitives
- Tightening the workspace-scoped AI token model (budgets, rotation, audit)
- A real-world demo corpus: World Bank GDP, 30 countries × 15 years (2009–2023)

---

<p align="center"><sub>Built quietly. Shipping soon.</sub></p>
