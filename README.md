<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:2EA043&height=170&section=header&text=Justin%20%7C%20Systems%20%26%20Backend&fontSize=34&fontColor=ffffff&fontAlignY=38&desc=12%2C000%2B%20RPS%20Fintech%20%E2%80%A2%20%3E80%25%20Latency%20Cut%20%E2%80%A2%20Production%20RAG&descSize=15&descAlignY=60" width="100%" alt="Header Banner" />

📍 **Lviv, Ukraine** &nbsp;|&nbsp; 🎓 **M.Sc. in Computer Programming** @ Ukrainian Catholic University

[![Open to Work](https://img.shields.io/badge/Status-Open_to_Senior_Roles_%26_Consulting-2EA043?style=for-the-badge&logo=target&logoColor=white)](https://www.linkedin.com/in/lshbss-undefined-366b05451/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lshbss-undefined-366b05451/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lshbss)

<br/>

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="460" alt="Coding animation" />

</div>

---

### 🤝 Open to Opportunities

Currently open to **Senior Full-Stack / Backend Engineering roles** and **high-impact consulting projects** (Remote / Worldwide):
- **Core Focus:** High-throughput distributed backends, fintech payment systems, database performance tuning, and production AI / RAG pipelines.
- **Best Way to Reach Out:** Drop a message on [LinkedIn](https://www.linkedin.com/in/lshbss-undefined-366b05451/) — happy to discuss system architecture, scaling challenges, or open roles.

---

### ⚡ What I Do & Production Impact

- **High-Throughput Fintech & Payments:** Architected append-only ledgers, strict payout state machines, and idempotent payment APIs scaling up to **12,000 RPS** (`p95: 110–130ms`) with automated zero-delta nightly reconciliation.
- **Database & Latency Optimization:** Reduced slow query latencies by **>80%** (`2.6s → 410ms`) via PostgreSQL read-replica routing, keyset pagination, MongoDB compound indexes, and Redis Cluster caching (`90%+` hit ratio) with atomic Lua rate-limiting.
- **Production AI & RAG Pipelines:** Engineered fault-tolerant retrieval workflows, token streaming, strict Zod schema validation, and nightly regression evals with field-level diffing to catch model/prompt drift.
- **Reliability & Observability:** End-to-end production ownership across AWS (S3, CloudWatch), Docker, GitHub Actions CI/CD, k6 load testing, Prometheus, Grafana, and Sentry.

---

### 🧠 Engineering Principles

```ts
const engineeringMindset = {
  dataIntegrity: "Append-only ledgers + idempotency keys > optimistic assumptions",
  performance:   "Measure with k6, push filtering to DB, cache hot paths in Redis",
  aiInProd:      "Never trust raw LLM output — enforce Zod schemas & nightly evals",
  observability: "If it's not traced with correlation IDs and alerts, it's not prod-ready",
};
