<div align="center">

  <h1>Justin &mdash; Distributed Systems &amp; Backend Engineer</h1>

  <p>
    <b>12,000+ RPS Fintech Ledgers</b> &bull; <b>&gt;80% DB Latency Reduction</b> &bull; <b>Deterministic AI Pipelines</b>
  </p>

  <p>
    📍 Lviv, Ukraine &nbsp;&bull;&nbsp; 🎓 M.Sc. in Computer Programming (UCU) &nbsp;&bull;&nbsp; 🟢 <b>Open to Senior Roles &amp; Consulting</b>
  </p>

  <p>
    <a href="https://www.linkedin.com/in/lshbss-undefined-366b05451/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/lshbss">
      <img src="https://img.shields.io/badge/GitHub-lshbss-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>

---

### ⚡ Production Impact & Architecture

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>💸 High-Throughput Fintech Core</h4>
      <ul>
        <li>Engineered append-only double-entry ledgers &amp; strict payout state machines.</li>
        <li>Scaled payment APIs to <b>12,000 RPS</b> (<code>p95: 110–130ms</code>) with idempotency keys.</li>
        <li>Built automated zero-delta nightly reconciliation pipelines.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🚀 Database &amp; Latency Engineering</h4>
      <ul>
        <li>Cut slow query latency by <b>&gt;80%</b> (<code>2.6s &rarr; 410ms</code>) via read-replica routing &amp; keyset pagination.</li>
        <li>Designed <b>Redis Cluster</b> caching (<code>90%+</code> hit ratio) with atomic <b>Lua</b> rate-limiting.</li>
        <li>Tuned high-volume MongoDB workloads using targeted compound indexes.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Deterministic AI &amp; RAG Systems</h4>
      <ul>
        <li>Built fault-tolerant hybrid RAG retrieval workflows with SSE token streaming.</li>
        <li>Enforced strict runtime output contracts via <b>Zod</b> schemas.</li>
        <li>Automated nightly regression evals with field-level diffing to catch model drift.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🛡 Reliability &amp; Observability</h4>
      <ul>
        <li>Full production ownership across <b>AWS</b> (S3, CloudWatch) &amp; Dockerized microservices.</li>
        <li>Load &amp; stress verification with <b>k6</b> before major releases.</li>
        <li>End-to-end telemetry via Prometheus, Grafana, Sentry &amp; GitHub Actions CI/CD.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠 Engineering Stack

| Domain | Technologies & Tools |
| :--- | :--- |
| **Backend & Architecture** | <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" /> <img src="https://img.shields.io/badge/BullMQ-FF6F00?style=flat-square" /> |
| **Data & Caching** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> |
| **AI & Validation** | <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" /> <img src="https://img.shields.io/badge/RAG-10A37F?style=flat-square" /> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" /> |
| **Frontend & Infra** | <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" /> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" /> <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" /> |

---

### 🧠 Engineering Philosophy

```ts
const systemDesignRules = {
  ledgerIntegrity: "Append-only entries + idempotency keys >
