# 📚 PROCUX Developer Documentation

[![PROCUX](https://img.shields.io/badge/PROCUX-Decision_Infrastructure-000000?style=flat-square)](https://procux.com)
[![License](https://img.shields.io/badge/License-CC_BY_NC_4.0-lightgrey?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

> Architecture guides, integration references, and developer documentation for the PROCUX B2B decision infrastructure.

---

## 📖 Contents

### Architecture
- **[Ecosystem Overview](docs/architecture/ecosystem-overview.md)** — How 7 platforms connect as a unified decision infrastructure
- **[Data Flow](docs/architecture/data-flow.md)** — Demand → AI Analysis → Payment → Logistics → Feedback cycle
- **[Multi-Agent System](docs/architecture/multi-agent-overview.md)** — 16 AI agents, orchestration patterns, and 3-layer guardrails
- **[Security Architecture](docs/architecture/security.md)** — 17-layer security model overview

### Integration Guides
- **[Supplier Onboarding](docs/integration/supplier-onboarding.md)** — How suppliers connect to the ecosystem
- **[Webhook Events](docs/integration/webhooks.md)** — Event types, payloads, and retry policies
- **[Authentication](docs/integration/authentication.md)** — JWT, CSRF, and API key management

### AI Modules *(Research)*
- **[Demand Forecasting](docs/ai/demand-forecasting.md)** — Hybrid forecasting approach
- **[Dynamic Pricing](docs/ai/dynamic-pricing.md)** — Clustering + scoring engine
- **[Supplier Ranking](docs/ai/supplier-ranking.md)** — Multi-criteria ranking methodology
- **[NLP Pipeline](docs/ai/nlp-pipeline.md)** — Turkish B2B text analysis

---

## ⚙️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Backend** | Python · FastAPI · SQLAlchemy (async) · Celery · Redis |
| **Frontend** | Next.js 15 · React 19 · TypeScript · Tailwind CSS · Zustand |
| **Database** | PostgreSQL · pgvector (HNSW) · Redis |
| **AI/ML** | Transformer models · XGBoost · LSTM · Clustering · Learning-to-Rank |
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

