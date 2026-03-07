<div align="center">

<img src="https://img.shields.io/badge/Section-Getting%20Started-7C3AED?style=for-the-badge&logo=rocket&logoColor=white" alt="Getting Started" />
<img src="https://img.shields.io/badge/Audience-All%20Users-blue?style=for-the-badge&logo=people&logoColor=white" alt="All Users" />
<img src="https://img.shields.io/badge/Reading_Time-5_min-green?style=for-the-badge&logo=clock&logoColor=white" alt="5 min read" />

# 🚀 Introduction to SaaSIQ

**Everything you need to know about the platform before diving in**

`Home` · `Getting Started` · **Introduction**

</div>

---

## What is SaaSIQ?

SaaSIQ is an **AI-powered SaaS Management Platform** designed to give organizations complete visibility and control over their software-as-a-service portfolio. It solves the growing challenge of **SaaS sprawl** — where companies unknowingly accumulate dozens or hundreds of cloud applications, leading to wasted spend, security gaps, and compliance risks.

### The Problem SaaSIQ Solves

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#7C3AED', 'primaryTextColor': '#fff', 'primaryBorderColor': '#5B21B6', 'lineColor': '#7C3AED', 'secondaryColor': '#FEE2E2', 'tertiaryColor': '#F5F3FF', 'fontFamily': 'Inter'}}}%%
graph LR
    A["😰 SaaS Sprawl"] -->|causes| B["💸 Wasted Spend"]
    A -->|creates| C["🔓 Shadow IT Risks"]
    A -->|leads to| D["📋 Compliance Gaps"]
    A -->|results in| E["📉 Low Utilization"]
    
    F["✨ SaaSIQ"] -->|delivers| G["💰 30% Cost Savings"]
    F -->|provides| H["🔒 Full Visibility"]
    F -->|ensures| I["✅ Automated Compliance"]
    F -->|optimizes| J["📊 License Utilization"]

    style A fill:#FEE2E2,stroke:#DC2626,stroke-width:2px
    style F fill:#EDE9FE,stroke:#7C3AED,stroke-width:2px
    style B fill:#FEF3C7,stroke:#D97706
    style C fill:#FEF3C7,stroke:#D97706
    style D fill:#FEF3C7,stroke:#D97706
    style E fill:#FEF3C7,stroke:#D97706
    style G fill:#D1FAE5,stroke:#059669
    style H fill:#D1FAE5,stroke:#059669
    style I fill:#D1FAE5,stroke:#059669
    style J fill:#D1FAE5,stroke:#059669
```

| Challenge | How SaaSIQ Helps |
|-----------|-----------------|
| **Shadow IT** — Employees adopt apps without IT approval | AI-powered discovery finds every app across your org |
| **Wasted licenses** — Paying for seats nobody uses | Usage analytics identifies underutilized licenses |
| **Overspending** — No visibility into total SaaS cost | Spend intelligence with AI-driven optimization |
| **Compliance risk** — Apps that don't meet security standards | Automated compliance monitoring against SOC 2, GDPR, HIPAA, ISO 27001 |
| **Manual renewals** — Contracts slip through the cracks | Proactive renewal calendar with negotiation assistance |
| **Offboarding gaps** — Former employees retain access | Automated license revocation tied to HR systems |

---

## Who is SaaSIQ For?

<table>
<tr>
<td width="50%">

<details open>
<summary><strong>🏢 IT Administrators & Managers</strong></summary>

- Get a complete inventory of all SaaS applications
- Approve, block, or monitor applications
- Manage integrations with SSO, HRIS, and finance systems
- Control access and enforce security policies

**Start here →** [SaaS Discovery](../intelligence/saas-discovery.md)

</details>

<details open>
<summary><strong>💰 Finance & Procurement Teams</strong></summary>

- Understand total SaaS spend by department, vendor, or category
- Identify cost savings through optimization recommendations
- Benchmark your pricing against industry peers
- Track ROI of SaaS investments

**Start here →** [Spend Intelligence](../intelligence/spend-intelligence.md)

</details>

</td>
<td width="50%">

<details open>
<summary><strong>🛡️ Security & Compliance Officers</strong></summary>

- Monitor compliance with SOC 2, GDPR, HIPAA, ISO 27001
- Identify and remediate high-risk applications
- Enforce data residency and security policies
- Audit vendor certifications and DPA agreements

**Start here →** [Compliance & Risk](../governance/compliance-and-risk.md)

</details>

<details open>
<summary><strong>👔 C-Suite & Department Heads</strong></summary>

- High-level dashboards showing SaaS health at a glance
- AI-generated insights and predictions
- Department-level cost accountability
- Strategic planning with benchmark data

**Start here →** [Dashboard](../overview/dashboard.md)

</details>

</td>
</tr>
</table>

---

## Core Concepts

> [!NOTE]
> These are the fundamental building blocks you'll see across every module. Understanding them first will make the rest of the documentation much clearer.

### 🔍 SaaS Discovery

SaaSIQ automatically discovers applications used across your organization by analyzing SSO logs, browser activity, expense reports, and API integrations. Apps are classified as **Managed** (IT-approved) or **Shadow IT** (unapproved).

### 💰 Spend Intelligence

AI analyzes your SaaS contracts, invoices, and usage data to calculate the **true cost** of each tool — then recommends optimizations like downgrading unused licenses, consolidating overlapping tools, or negotiating better pricing.

### 📊 Usage Analytics

Every application is tracked for **utilization rate** — the percentage of purchased licenses actively being used. Low utilization triggers recommendations for license reclamation or plan downgrades.

### 🛡️ Compliance & Risk

Each application receives a **risk score** based on its security certifications, data handling practices, and alignment with your compliance frameworks. High-risk apps are flagged for immediate review.

### 🤖 AI Copilot

A conversational AI assistant that understands your entire SaaS landscape. Ask questions in natural language — *"Which apps have the lowest utilization?"* or *"How much can we save on Slack?"* — and get data-driven answers instantly.

---

## Platform Architecture

SaaSIQ follows a **modular architecture** organized around six core pillars:

```
┌─────────────────────────────────────────────────────────────┐
│                    SaaSIQ Platform                           │
├──────────┬──────────┬──────────┬──────────┬────────┬────────┤
│ 🔍       │ 💰       │ 🛡️      │ 🤖       │ ⚙️     │ 🔧     │
│ Discovery│ Spend    │ Govern-  │ AI       │ Opera- │ Admin  │
│ & Shadow │ Intelli- │ ance     │ Features │ tions  │        │
│ IT       │ gence    │          │          │        │        │
├──────────┼──────────┼──────────┼──────────┼────────┼────────┤
│ App      │ Cost     │ Compli-  │ Insights │ Off-   │ Alerts │
│ Inventory│ Analysis │ ance     │          │ board  │        │
│          │          │          │          │        │        │
│ Approve/ │ Optimi-  │ Contracts│ Copilot  │ Renew- │ Sett-  │
│ Block    │ zations  │          │          │ als    │ ings   │
│          │          │          │          │        │        │
│ Re-scan  │ Bench-   │ Policies │          │ Bench- │ Org    │
│          │ marks    │          │          │ marks  │ Mgmt   │
└──────────┴──────────┴──────────┴──────────┴────────┴────────┘
```

---

## What's Inside This Documentation

| Section | What You'll Learn |
|---------|------------------|
| [Quick Start Guide](quick-start.md) | How to get from zero to your first dashboard in under 10 minutes |
| [Onboarding Wizard](onboarding.md) | The 4-step setup process every new organization goes through |
| [Dashboard](../overview/dashboard.md) | Understanding your command center — KPIs, charts, and alerts |
| [Intelligence](../intelligence/index.md) | Discovering apps, optimizing spend, and tracking usage |
| [Governance](../governance/index.md) | Compliance monitoring, contract management, and policy enforcement |
| [AI Features](../ai-features/index.md) | AI Insights and the conversational AI Copilot |
| [Operations](../operations/index.md) | Offboarding, renewals, benchmarks, and department cost analysis |
| [Administration](../administration/index.md) | Alerts, settings, team management, and org controls |

---

## What's Next?

Ready to get started? Follow the path that fits your role:

| Your Role | Start Here |
|-----------|-----------|
| **First-time user** | → [Quick Start Guide](quick-start.md) |
| **Evaluating SaaSIQ** | → [Dashboard Overview](../overview/dashboard.md) |
| **IT Administrator** | → [SaaS Discovery](../intelligence/saas-discovery.md) |
| **Finance/Procurement** | → [Spend Intelligence](../intelligence/spend-intelligence.md) |
| **Security/Compliance** | → [Compliance & Risk](../governance/compliance-and-risk.md) |

---

---

<div align="center">

**Was this page helpful?** 👍 Yes · 👎 No · [Suggest an edit](https://github.com/saasiq/saasiq-documentation/edit/main/docs/getting-started/introduction.md)

---

<a href="../README.md">⬅️ Documentation Home</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="quick-start.md">Quick Start Guide ➡️</a>

<sub>Last updated: March 2026 · SaaSIQ Documentation v1.0.0</sub>

</div>
