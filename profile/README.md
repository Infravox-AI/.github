<div align="center">

<img src="https://infravox.ai/favicon.ico" width="60" alt="Infravox AI" />

# Infravox AI

### The Autonomous Engineering Operating System

**Monitor. Diagnose. Remediate. Learn. — Automatically. 24/7.**

[![Website](https://img.shields.io/badge/infravox.ai-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://infravox.ai)
[![Docs](https://img.shields.io/badge/Documentation-3B82F6?style=for-the-badge&logo=gitbook&logoColor=white)](https://infravox.ai/docs)
[![CLI](https://img.shields.io/badge/@infravox/cli-00E5FF?style=for-the-badge&logo=gnometerminal&logoColor=black)](https://infravox.ai/cli)
[![Guides](https://img.shields.io/badge/Guides-6366F1?style=for-the-badge&logo=readme&logoColor=white)](https://infravox.ai/docs)
[![Pricing](https://img.shields.io/badge/Pricing-8B5CF6?style=for-the-badge&logo=stripe&logoColor=white)](https://infravox.ai/pricing)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/infravox-ai)

</div>

---

## What is Infravox AI?

Infravox AI is **the first AI-native autonomous infrastructure operating system** — a production-grade SaaS platform that replaces 80% of manual DevOps, SRE, and FinOps workflows using six specialist AI agents working together 24/7.

This is **not** a monitoring dashboard. This is **not** a chatbot wrapper.

This is an autonomous OS that:
- **Detects** anomalies across your entire stack in under 60 seconds
- **Diagnoses** root cause with 94% confidence using ML-powered analysis
- **Executes** safe, reversible fixes — restart, rollback, scale, patch
- **Verifies** recovery and auto-generates postmortems
- **Learns** from every incident using vector-based AI memory

> **Average MTTR: 4+ hours → 94 seconds. No 3AM pages. No manual toil.**

---

## Six Specialist AI Agents

```
┌──────────────────────────────────────────────────────────────────────────┐
│                          AI Orchestrator                                 │
│          Routes signals · Combines multi-agent outputs · Decides        │
└────┬──────────┬──────────┬──────────┬──────────┬───────────┘
     │          │          │          │          │
  SRE        Kubernetes  Security  FinOps    CI/CD      Code Review
  Agent       Agent       Agent     Agent    Agent        Agent
```

| Agent | Capability |
|---|---|
| 🧠 **SRE Agent** | 24/7 incident detection, ML root cause analysis, auto-remediation with blast-radius control |
| ☸️ **Kubernetes Agent** | Pod health, HPA analysis, deployment monitoring, cluster auto-healing |
| 🔐 **Security Agent** | CVE scanning, RBAC audits, IAM misconfiguration detection, SOC2/HIPAA/GDPR compliance |
| 💰 **FinOps Agent** | Cloud waste detection, rightsizing, idle resource cleanup — $2K–$15K/mo savings |
| 🚀 **CI/CD Agent** | Pipeline failure detection, rollback recommendations, deployment risk analysis |
| 🔀 **Code Review Agent** | AI PR reviews, SAST scanning, secret detection, merge blocking on critical findings |

---

## Platform Capabilities

### 🚨 AI War Room
Real-time collaborative incident command center. When a P0 fires, the War Room preloads logs, metrics, AI findings, and blast radius. Type `fix it` and watch autonomous remediation execute live.

```
P0 INCIDENT  →  War Room opens automatically
               →  3 agents engaged in parallel
               →  Root cause identified in <30s
               →  Approval gate → "Approve & Execute"
               →  Fix deployed + verified in 94s
               →  Postmortem auto-generated ✅
```

### 💻 DevOps CLI — `@infravox/cli`
Your terminal is the Infravox OS. Full platform parity with the web UI.

```bash
npm install -g @infravox/cli

infravox diagnose payment-api        # AI root cause analysis
infravox optimize aws-cost           # Cloud cost scan
infravox fix kubernetes-latency      # Autonomous K8s remediation
infravox scan security --pr 1842     # Security scan on a PR
infravox agents status               # View all 6 AI agents live
infravox logs tail --service api     # Stream live logs
infravox war-room open               # Open AI War Room
infravox rollback cart-service       # One-command rollback
```

### 🔭 Infrastructure Topology Graph
AI-powered knowledge graph of your entire infrastructure — services, pods, databases, cloud resources, dependencies. AI reasons over graph relationships for faster root cause correlation.

### 📊 AI Change Impact Analysis
Before every deploy, Infravox scores deployment risk, maps dependency blast radius, and recommends whether to proceed, canary, or hold.

### 💾 RAG + AI Memory
Vector-based long-term AI memory per tenant. Agents learn your infrastructure patterns, incident history, and runbooks over time — getting smarter with every incident resolved.

---

## Autonomous Remediation Flow

```
Alert fires
    ↓
AI Triage  (<30s)  —  6 agents collaborate in parallel
    ↓
Root Cause  (94% confidence)  —  logs · metrics · topology · git diff
    ↓
Fix proposed  —  ranked · reversible · blast-radius scored
    ↓
Execute  →  kubectl / AWS SDK / CI/CD API / Helm (via MCP protocol)
    ↓
Verify  →  health checks pass
    ↓
Close + Postmortem  +  AI memory updated  ✅

Dry-run mode · Approval gates · Rollback built-in · Full audit trail
```

---

## Integrations — 40+ Native Connectors

### ☁️ Cloud
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

### 🔀 Source Control
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat&logo=bitbucket&logoColor=white)
![Azure Repos](https://img.shields.io/badge/Azure_Repos-0078D4?style=flat&logo=azuredevops&logoColor=white)

### ⚙️ CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D33833?style=flat&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-00BCF2?style=flat&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat&logo=circleci&logoColor=white)

### 📡 Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-008C99?style=flat&logo=newrelic&logoColor=white)
![Loki](https://img.shields.io/badge/Grafana_Loki-F46800?style=flat&logo=grafana&logoColor=white)

### 🔔 Alerting
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)
![PagerDuty](https://img.shields.io/badge/PagerDuty-06AC38?style=flat&logo=pagerduty&logoColor=white)
![Teams](https://img.shields.io/badge/Microsoft_Teams-5059C9?style=flat&logo=microsoftteams&logoColor=white)
![Opsgenie](https://img.shields.io/badge/Opsgenie-EF5C23?style=flat&logo=opsgenie&logoColor=white)

---

## Impact Metrics

| Metric | Result |
|---|---|
| ⏱ **MTTR** | 4 hours → **94 seconds** |
| 🤖 **Auto-resolve rate** | **78%** of incidents |
| 💰 **Monthly savings** | **$8,340** avg per team |
| 🕐 **Engineer hours saved** | **40+ hours/month** |
| 📈 **ROI** | **21×** on Growth plan |
| 🔐 **Compliance checks** | **580+** automated |
| ☁️ **Cloud waste reduced** | Avg **$2K–$15K/month** |

---

## Pricing

| Plan | Price | Clusters | AI Ops/Month | Key Features |
|---|---|---|---|---|
| 🆓 **Free** | $0 | 1 | 100 | Basic AI monitoring, community support |
| ⚡ **Starter** | $99/mo | 2 | 2,000 | AI RCA, Slack alerts, AI PR reviews |
| 🔥 **Growth** | $499/mo | 10 | 20,000 | AI War Room, Security AI, FinOps AI, autonomous remediation |
| 🏢 **Scale** | $1,499/mo | Unlimited | High-volume | SSO/SAML, RBAC, audit logs, API access, 99.95% SLA |
| 🌐 **Enterprise** | Custom | Unlimited | Enterprise | VPC/on-prem, private AI, SOC2/HIPAA/ISO, dedicated support |

> **Usage-based add-ons**: `$5/node · $0.25/GB logs · AI ops overage pricing available`

---

## Enterprise Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                   Multi-Tenant SaaS Layer                   │
│  Organization → Projects → Teams → RBAC → Audit Logs       │
├─────────────────────────────────────────────────────────────┤
│                  Secure Secrets Vault                       │
│  AES-256 encrypted · Per-tenant isolation · Zero plaintext  │
├─────────────────────────────────────────────────────────────┤
│               AI Agent Orchestration Engine                 │
│  6 agents · Redis pub/sub · Celery workers · Event bus      │
├──────────────┬──────────────┬──────────────────────────────┤
│  FastAPI     │  PostgreSQL  │  pgvector (AI memory)        │
│  Backend     │  + Redis     │  RAG pipeline                │
└──────────────┴──────────────┴──────────────────────────────┘
```

**Enterprise security**: SOC2-ready · SSO/SAML · VPC deployment · Immutable audit logs · Multi-tenant RBAC · TLS everywhere · AI safety controls

---

## Tech Stack

```
Frontend    →  Next.js 15 (App Router) · React · TypeScript · Tailwind CSS
Backend     →  FastAPI (Python) · PostgreSQL · Redis · Celery
AI Layer    →  Multi-agent orchestration · RAG + pgvector · MCP Protocol
Observability → ClickHouse · Loki · Prometheus · OpenTelemetry · Tempo
Infrastructure → Kubernetes-native · Docker · Helm charts · Terraform
Auth        →  JWT · OAuth2 · Google SSO · GitHub SSO · SAML 2.0
Real-time   →  WebSockets + SSE — live agent feed · War Room · log streaming
CLI         →  @infravox/cli (npm) — full platform terminal access
```

---

## Quick Start

```bash
# 1. Sign up free at infravox.ai — no credit card needed
# 2. Connect your cloud (AWS / GCP / Azure) — OAuth, 2 minutes
# 3. Connect Kubernetes cluster via Helm
helm repo add infravox https://charts.infravox.ai
helm install infravox-operator infravox/infravox-operator \
  --namespace infravox-system --create-namespace \
  --set apiKey=YOUR_KEY --set cluster.name=production

# 4. Install the CLI
npm install -g @infravox/cli
infravox auth login
infravox scan --all

# From alert to autonomous in 30 minutes.
```

📖 Full onboarding guides at [infravox.ai/docs](https://infravox.ai/docs)

---

## Documentation

| Resource | Link |
|---|---|
| 📖 **Full Docs** | [infravox.ai/docs](https://infravox.ai/docs) |
| 🚀 **Install Guide** | [infravox.ai/docs → Getting Started](https://infravox.ai/guides/install) |
| ☸️ **Connect Kubernetes** | [infravox.ai/guides/connect-k8s](https://infravox.ai/guides/connect-k8s) |
| 💻 **CLI Reference** | [infravox.ai/cli](https://infravox.ai/cli) |
| 🤖 **AI Agent Permissions** | [infravox.ai/guides/agent-permissions](https://infravox.ai/guides/agent-permissions) |
| 💰 **Pricing** | [infravox.ai/pricing](https://infravox.ai/pricing) |
| 🏢 **About** | [infravox.ai/about](https://infravox.ai/about) |

---

## Team

<table>
<tr>
<td align="center" width="280">
<img src="https://infravox.ai/team/shivam.png" width="120" height="120" style="border-radius:50%" alt="Shivam Singh" /><br />
<strong>Shivam Singh</strong><br />
CEO & Co-Founder<br />
<sub>Kubernetes · AI/ML · Cloud Infrastructure · Platform Engineering</sub><br /><br />
<a href="mailto:shivamsingh@infravox.ai">📩 shivamsingh@infravox.ai</a><br />
<a href="https://www.linkedin.com/in/shivam-chauhan-b053a9174/">💼 LinkedIn</a> ·
<a href="https://github.com/shivamsingh-Infravoxai">🐙 GitHub</a>
</td>
<td align="center" width="280">
<img src="https://infravox.ai/team/sameer.png" width="120" height="120" style="border-radius:50%" alt="Sameer Bhanot" /><br />
<strong>Sameer Bhanot</strong><br />
COO & Chief Product Officer<br />
<sub>Product Strategy · GTM & Sales · SaaS Growth · Operations</sub><br /><br />
<a href="mailto:sameer@infravox.ai">📩 sameer@infravox.ai</a><br />
<a href="https://www.linkedin.com/in/sameer-bhanot-75a25a172/">💼 LinkedIn</a>
</td>
</tr>
</table>

**We're hiring**: Head of Engineering · Lead AI/ML Researcher · Senior SRE · Growth Lead  
→ [hello@infravox.ai](mailto:hello@infravox.ai)

---

<div align="center">

**Infravox AI · Founded 2026 · Remote-first · Production Ready**

*The Autonomous Engineering Operating System — built for teams that never want to fight fires again.*

[![Try Free](https://img.shields.io/badge/Try_Free-Get_Started-6366F1?style=for-the-badge)](https://infravox.ai)
[![Book Architecture Review](https://img.shields.io/badge/Enterprise-Book_Architecture_Review-10B981?style=for-the-badge)](mailto:shivamsingh@infravox.ai?subject=Architecture%20Review%20-%20Infravox%20AI)
[![CLI Docs](https://img.shields.io/badge/npm_install-@infravox/cli-00E5FF?style=for-the-badge&logo=npm)](https://infravox.ai/cli)

⭐ **Star this org** if autonomous infrastructure is the future you believe in.

</div>
