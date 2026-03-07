<div align="center">

<img src="https://img.shields.io/badge/📚_Reference-FAQ-0891B2?style=for-the-badge&logo=bookstack&logoColor=white" alt="Reference — FAQ" />
<img src="https://img.shields.io/badge/Questions-20+-0891B2?style=for-the-badge" alt="20+ Questions" />
<img src="https://img.shields.io/badge/Updated-2024-0891B2?style=for-the-badge" alt="Updated" />

# ❓ Frequently Asked Questions

**Quick answers to common questions about SaaSIQ features & workflows**

`Home` · `Reference` · **`FAQ`**

</div>

---

## Overview

Answers to the most commonly asked questions about SaaSIQ. Questions are organized by category — click any section to expand.

---

## In This Article

- [General](#general)
- [Getting Started](#getting-started)
- [SaaS Discovery](#saas-discovery)
- [Spend & Cost Management](#spend--cost-management)
- [Compliance & Governance](#compliance--governance)
- [AI Features](#ai-features)
- [Security & Privacy](#security--privacy)
- [Billing & Plans](#billing--plans)
- [Troubleshooting](#troubleshooting)

---

## General

<details>
<summary><strong>What is SaaSIQ?</strong></summary>

SaaSIQ is an **AI-powered SaaS Management Platform** that helps organizations discover, manage, optimize, and govern their entire SaaS portfolio. It provides visibility into shadow IT, spend analytics, compliance tracking, and AI-driven recommendations.

→ Learn more: [Introduction](../getting-started/introduction.md)

</details>

<details>
<summary><strong>Who is SaaSIQ designed for?</strong></summary>

SaaSIQ serves four primary personas:

| Role | Primary Use |
|------|-------------|
| **IT Administrators** | Discover apps, manage licenses, offboard users |
| **Finance Teams** | Track spend, optimize costs, benchmark pricing |
| **Security & Compliance** | Monitor compliance frameworks, assess risk, enforce policies |
| **C-Suite / Leadership** | Get portfolio overview, ROI reporting, executive dashboards |

</details>

<details>
<summary><strong>Is SaaSIQ a real SaaS management tool or a prototype?</strong></summary>

SaaSIQ is currently a **fully interactive UX prototype** built as a single-page application. It demonstrates the complete user journey with realistic demo data (TechCorp India). All UI interactions work — buttons open modals, navigation flows between pages, and AI features respond with pre-built data.

**Live Demo:** [https://saasiq.github.io/saasiq-ux-prototype/](https://saasiq.github.io/saasiq-ux-prototype/)

</details>

<details>
<summary><strong>What technologies power SaaSIQ?</strong></summary>

| Layer | Technology |
|-------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Routing | Hash-based SPA routing |
| Design System | Custom (Primary: `#7C3AED`, Font: Inter) |
| Hosting | GitHub Pages |
| AI Features | Simulated with pre-built response data |

</details>

---

## Getting Started

<details>
<summary><strong>How do I access SaaSIQ?</strong></summary>

1. Open [https://saasiq.github.io/saasiq-ux-prototype/](https://saasiq.github.io/saasiq-ux-prototype/)
2. You'll land on the **Landing Page**
3. Click **"Start Free Trial"** or **"Login"**
4. Use demo credentials: `demo@saasiq.io` / `SaaSIQ2024!`

→ Full walkthrough: [Quick Start](../getting-started/quick-start.md)

</details>

<details>
<summary><strong>What are the demo credentials?</strong></summary>

| Field | Value |
|-------|-------|
| **Email** | `demo@saasiq.io` |
| **Password** | `SaaSIQ2024!` |
| **Organization** | TechCorp India |
| **Role** | Admin |
| **Plan** | Business |

</details>

<details>
<summary><strong>Can I skip the onboarding wizard?</strong></summary>

Yes. On the onboarding screen, look for **"Skip for now"** at the bottom of each step. You can return to onboarding later from **Settings → Organization**.

> [!WARNING]
> Skipping onboarding means integrations won't be connected and team members won't be invited until you complete those steps manually.

</details>

---

## SaaS Discovery

<details>
<summary><strong>What is Shadow IT?</strong></summary>

Shadow IT refers to **SaaS applications adopted by employees without IT approval**. These apps may not meet security standards, lack DPAs, or create compliance risks. SaaSIQ automatically discovers Shadow IT through integration scanning and categorizes apps as:

- **Managed** (IT-approved) — 148 apps in demo
- **Shadow IT** (unapproved) — 8 apps in demo

→ Learn more: [SaaS Discovery](../intelligence/saas-discovery.md)

</details>

<details>
<summary><strong>How do I approve a Shadow IT app?</strong></summary>

1. Navigate to **SaaS Discovery** (`G` then `S`)
2. Find the app in the **Shadow IT** section
3. Click the **"Approve"** button on its card
4. In the modal, set:
   - Department assignment
   - License limit
   - Policy association
5. Click **"Approve & Add to Managed"**

The app moves from Shadow IT to Managed Apps. Its badge changes from 🔴 to 🟢.

</details>

<details>
<summary><strong>How do I block a Shadow IT app?</strong></summary>

1. Navigate to **SaaS Discovery**
2. Click **"Block"** on a Shadow IT app card
3. In the confirmation modal, select a reason:
   - Security Risk
   - Compliance Violation
   - Duplicate Functionality
   - Cost Concerns
4. Optionally add notes
5. Click **"Block Application"**

Blocked apps are flagged for removal and affected users are notified.

</details>

---

## Spend & Cost Management

<details>
<summary><strong>How is "Total SaaS Spend" calculated?</strong></summary>

Total SaaS Spend is the sum of all active SaaS subscription costs across all departments. In the demo:

| Metric | Value |
|--------|-------|
| **Monthly Spend** | ₹42.5 Lakhs |
| **Annual Spend** | ₹4.8 Crores |
| **Waste (unused licenses)** | ₹7 Lakhs/month |
| **Potential Savings** | ₹18 Lakhs/year |

</details>

<details>
<summary><strong>What are AI-recommended optimizations?</strong></summary>

SaaSIQ's AI analyzes usage patterns, contract terms, and market benchmarks to generate recommendations. Each recommendation includes:

- **Title** — what to do (e.g., "Consolidate Zoom + Teams")
- **Confidence Score** — how certain the AI is (0–100%)
- **Estimated Savings** — projected monthly/annual savings
- **Actions** — Apply, Review Details, or Create Savings Plan

→ Learn more: [Spend Intelligence](../intelligence/spend-intelligence.md)

</details>

<details>
<summary><strong>How do I benchmark our spending against industry?</strong></summary>

Navigate to **Benchmarks** (`G` then `B`). The page shows:

1. **KPI comparison cards** — your spend vs. industry average
2. **Vendor benchmark table** — per-vendor pricing comparison
3. **Negotiation tips** — AI-generated leverage points

→ Learn more: [Benchmarks](../operations/benchmarks.md)

</details>

---

## Compliance & Governance

<details>
<summary><strong>What compliance frameworks does SaaSIQ track?</strong></summary>

SaaSIQ monitors four major frameworks:

| Framework | Demo Score | Description |
|-----------|-----------|-------------|
| **SOC 2** | 85% | Service organization controls for security & availability |
| **GDPR** | 91% | EU data protection regulation |
| **HIPAA** | 72% | US healthcare data protection |
| **ISO 27001** | 68% | International information security standard |

→ Learn more: [Compliance & Risk](../governance/compliance-and-risk.md)

</details>

<details>
<summary><strong>What does the Risk Score mean?</strong></summary>

The Risk Score (0–100) represents your organization's overall compliance posture:

| Grade | Score Range | Meaning |
|-------|------------|---------|
| A+ | 95–100 | Excellent — all frameworks compliant |
| A | 85–94 | Strong — minor gaps |
| B+ | 75–84 | Good — some attention needed |
| B | 65–74 | Moderate — action recommended |
| C+ | 55–64 | Below average — significant gaps |
| C or below | <55 | Critical — immediate action required |

**Demo value:** B+ (78/100)

</details>

<details>
<summary><strong>How do I create a governance policy?</strong></summary>

1. Navigate to **Policies** (`G` then `P`)
2. Click **"+ Create Policy"**
3. Complete the 4-step wizard:
   - **Step 1:** Policy Details (name, description, category)
   - **Step 2:** Define Rules (conditions and thresholds)
   - **Step 3:** Set Actions (notify, block, require approval)
   - **Step 4:** Review & Activate
4. Click **"Create Policy"**

→ Full guide: [Policies](../governance/policies.md)

</details>

---

## AI Features

<details>
<summary><strong>How does AI Copilot work?</strong></summary>

AI Copilot is a conversational assistant that answers questions about your SaaS portfolio. It responds to topics like:

- 💰 **"Show me spend analysis"** — breakdown by category
- 🔍 **"Shadow IT risks"** — unapproved apps list
- 📅 **"Upcoming renewals"** — next 90 days
- 🛡️ **"Compliance status"** — framework scores
- 📊 **"Usage patterns"** — utilization data

**Access:** Click the chat icon or press `⌘ + /` / `Ctrl + /`

→ Full guide: [AI Copilot](../ai-features/ai-copilot.md)

</details>

<details>
<summary><strong>Are AI recommendations accurate?</strong></summary>

Each AI recommendation includes a **Confidence Score** (0–100%). In the demo:

- **Cost Savings Opportunities:** 96% confidence
- **Renewal Predictions:** 89% confidence
- **Negotiation Insights:** 91% confidence

Scores above 85% are high-confidence. Always review recommendations before applying — the **"Review Details"** button shows the underlying data.

</details>

<details>
<summary><strong>Can I interact with AI Copilot using natural language?</strong></summary>

Yes. The Copilot accepts natural language queries. You can type questions like:
- "How much are we spending on Slack?"
- "Which apps are not SOC 2 compliant?"
- "What renewals are coming up?"

In the prototype, the Copilot responds to **5 predefined topics**. Other queries receive a helpful default response.

</details>

---

## Security & Privacy

<details>
<summary><strong>How does SaaSIQ protect my data?</strong></summary>

| Measure | Implementation |
|---------|----------------|
| **Encryption at Rest** | AES-256 |
| **Encryption in Transit** | TLS 1.3 |
| **Authentication** | SSO (Google, Microsoft, Okta) + MFA |
| **Access Control** | Role-Based (Admin, Manager, Analyst, Viewer) |
| **Session Management** | Configurable timeout (default: 30 min) |
| **Audit Logs** | All actions logged with timestamps |

</details>

<details>
<summary><strong>What roles and permissions exist?</strong></summary>

| Role | Access Level |
|------|-------------|
| **Admin** | Full access — all features, settings, user management |
| **Manager** | Read/write — most features; cannot manage billing or org settings |
| **Analyst** | Read-only with export — view dashboards, run reports, export data |
| **Viewer** | Read-only — view dashboards and reports only |

→ See: [Settings → Team Members](../administration/settings.md)

</details>

---

## Billing & Plans

<details>
<summary><strong>What plans does SaaSIQ offer?</strong></summary>

| Feature | Starter | Business | Enterprise |
|---------|---------|----------|------------|
| **Price** | $49/mo | $149/mo | Custom |
| **Apps** | Up to 50 | Up to 500 | Unlimited |
| **Users** | 5 | 25 | Unlimited |
| **AI Features** | Basic | Full | Full + Custom |
| **Integrations** | 5 | 20 | Unlimited |
| **Support** | Email | Priority | Dedicated CSM |
| **SSO** | ❌ | ✅ | ✅ |
| **API Access** | ❌ | ✅ | ✅ |

The demo uses the **Business Plan**.

</details>

---

## Troubleshooting

<details>
<summary><strong>The page is blank or not loading</strong></summary>

1. Check your internet connection
2. Try a hard refresh: `⌘ + Shift + R` (Mac) / `Ctrl + Shift + R` (Windows)
3. Clear browser cache
4. Try a different browser (Chrome, Firefox, Edge recommended)
5. The prototype is hosted at: [https://saasiq.github.io/saasiq-ux-prototype/](https://saasiq.github.io/saasiq-ux-prototype/)

</details>

<details>
<summary><strong>Login isn't working</strong></summary>

- Verify credentials: `demo@saasiq.io` / `SaaSIQ2024!`
- Check that "Remember me" is toggled if you want persistent sessions
- Google SSO button also works for demo access
- Try clearing cookies for the site

</details>

<details>
<summary><strong>A button or modal isn't responding</strong></summary>

- Ensure you're on the correct page (check the URL hash)
- Try closing any open modals first (`Escape` key)
- Some actions are only available to Admin users
- Hard refresh the page and try again

</details>

<details>
<summary><strong>Charts or data not displaying</strong></summary>

- SaaSIQ uses CSS-rendered charts — ensure JavaScript is enabled
- Charts require a minimum viewport width of 768px
- Try resizing your browser window
- Some charts animate on first load — wait 2-3 seconds

</details>

---

## Still Need Help?

| Channel | Details |
|---------|---------|
| **Documentation** | You're reading it! Use the sidebar to navigate. |
| **Email Support** | support@saasiq.io |
| **In-App Help** | Click the **❓** icon in the user menu |
| **Keyboard Shortcuts** | Press `?` anywhere in the app |

---

## Related Resources

- 🔗 [Glossary](glossary.md) — Terms and definitions
- 🔗 [Keyboard Shortcuts](keyboard-shortcuts.md) — Complete shortcut reference
- 🔗 [Introduction](../getting-started/introduction.md) — Getting started with SaaSIQ
- 🔗 [Quick Start](../getting-started/quick-start.md) — 5-minute setup guide

---

<div align="center">

**Was this helpful?** [👍 Yes](# "Helpful") · [👎 No](# "Not Helpful") · [✏️ Suggest Edit](# "Edit")

<a href="keyboard-shortcuts.md">⬅️ Keyboard Shortcuts</a>&nbsp;&nbsp;•&nbsp;&nbsp;<a href="../README.md">🏠 Documentation Home</a>

<sub>Last updated: 2024 · <a href="../README.md">🏠 Documentation Home</a></sub>

</div>
