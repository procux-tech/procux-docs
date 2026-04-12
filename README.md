# 📚 PROCUX Developer Documentation

[![PROCUX](https://img.shields.io/badge/PROCUX-Ecosystem-000000?style=flat-square)](https://procux.com)
[![License](https://img.shields.io/badge/License-CC_BY_NC_4.0-lightgrey?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

> Official documentation, architecture guides, and integration references for the PROCUX B2B procurement ecosystem.

---

## 📖 Contents

### Architecture

- **[Ecosystem Overview](docs/architecture/ecosystem-overview.md)** — How 7 platforms connect as a unified decision infrastructure
- **[Data Flow Architecture](docs/architecture/data-flow.md)** — Demand → AI Analysis → Payment → Logistics → Feedback cycle
- **[Multi-Agent System](docs/architecture/multi-agent-overview.md)** — 15 C-suite AI agents, orchestration patterns, and guardrails
- **[Security Architecture](docs/architecture/security.md)** — 17-layer security model overview

### Integration Guides

- **[Supplier Onboarding](docs/integration/supplier-onboarding.md)** — How suppliers connect to the PROCUX ecosystem
- **[Webhook Events](docs/integration/webhooks.md)** — Event types, payloads, and retry policies
- **[Authentication](docs/integration/authentication.md)** — JWT, CSRF, and API key management

### Platform Guides

- **[merkezisatinalma.com](docs/platforms/merkezisatinalma.md)** — B2B collective purchasing platform (live)
- **[Daily Pooling System](docs/platforms/daily-pooling.md)** — 17:00 close / 17:15 RFQ dispatch mechanism

### AI Modules *(Research)*

- **[Demand Forecasting](docs/ai/demand-forecasting.md)** — XGBoost + LSTM hybrid approach
- **[Dynamic Pricing](docs/ai/dynamic-pricing.md)** — HDBSCAN clustering + scoring engine
- **[Supplier Ranking](docs/ai/supplier-ranking.md)** — AHP + LambdaMART methodology
- **[NLP Pipeline](docs/ai/nlp-pipeline.md)** — BERTurk-based text analysis for Turkish B2B

---

## 🏗️ Ecosystem Map

```
Intelligence:  procux.com          — Multi-Agent AI Orchestration
Commerce:      merkezisatinalma.com — Collective Purchasing (TR)
               hubcux.com          — Collective Purchasing (Global)
               satinalmamerkezi.com — Group Buying (TR)
               buycux.com          — Group Buying (Global)
Infrastructure: paycux.com          — Embedded Fintech
               allicux.com         — Logistics Orchestration
```

---

## ⚙️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Backend** | Python · FastAPI · SQLAlchemy (async) · Celery · Redis |
| **Frontend** | Next.js 15 · React 19 · TypeScript · Tailwind CSS · Zustand |
| **Database** | PostgreSQL · pgvector (HNSW) · Redis |
| **AI/ML** | BERTurk · XGBoost · LSTM · HDBSCAN · LambdaMART |
| **Infra** | Docker · Vercel · Railway · GitHub Actions · GCP |

---

## 📬 Contact

- **Website:** [procux.com](https://procux.com)
- **Email:** info@procux.com
- **LinkedIn:** [PROCUX Technology](https://www.linkedin.com/company/procux-technology-inc/)

---

## 📄 License

Documentation is licensed under [CC BY-NC 4.0](LICENSE). Code samples are licensed under [MIT](LICENSE-CODE).

> ℹ️ *This repository contains documentation and architectural references only. Source code for PROCUX platforms is maintained in private repositories.*
