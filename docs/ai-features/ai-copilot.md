<div align="center">

<img src="https://img.shields.io/badge/Module-AI%20Features-DB2777?style=for-the-badge&logo=sparkles&logoColor=white" alt="AI Features" />
<img src="https://img.shields.io/badge/Feature-AI%20Copilot-blue?style=for-the-badge&logo=message&logoColor=white" alt="AI Copilot" />
<img src="https://img.shields.io/badge/Route-%23ai--copilot-orange?style=for-the-badge&logo=link&logoColor=white" alt="Route" />

# 🤖 AI Copilot

**Your conversational AI assistant for data-driven SaaS answers**

`Home` · `AI Features` · **AI Copilot**

</div>

> **Home** · AI Features · **AI Copilot**

---

## Overview

The AI Copilot is a **conversational AI assistant** that understands your entire SaaS portfolio. Ask questions in natural language — about spend, usage, compliance, renewals, or any aspect of your SaaS management — and get **data-driven, contextual answers** instantly.

It's like having a SaaS analyst on your team that has read every contract, analyzed every usage log, and memorized every compliance requirement.

---

## In This Article

- [Interface Layout](#interface-layout)
- [Suggested Questions](#suggested-questions)
- [Conversation Topics & Responses](#conversation-topics--responses)
- [How to Use Effectively](#how-to-use-effectively)
- [Validation Checklist](#validation-checklist)

---

## Interface Layout

```
┌──────────────────────────────────────────────────────────────┐
│  🤖 SaaSIQ AI Copilot                                [Clear]│
│                                                              │
│  ┌────────────────────────────────────────────────────────┐  │
│  │  Welcome! I'm your SaaSIQ AI Copilot. I can help you  │  │
│  │  with spend analysis, usage insights, compliance       │  │
│  │  questions, and more. Try asking me anything about     │  │
│  │  your SaaS portfolio.                                  │  │
│  └────────────────────────────────────────────────────────┘  │
│                                                              │
│  Suggested:                                                  │
│  ┌─────────────────┐ ┌──────────────────┐                   │
│  │ Where can we     │ │ Show shadow IT   │                   │
│  │ save money?      │ │ apps             │                   │
│  └─────────────────┘ └──────────────────┘                   │
│  ┌─────────────────┐ ┌──────────────────┐                   │
│  │ Upcoming         │ │ What's our       │                   │
│  │ renewals         │ │ compliance risk? │                   │
│  └─────────────────┘ └──────────────────┘                   │
│                                                              │
│  ┌──────────────────────────────────────────┐ ┌────┐        │
│  │ Ask me anything about your SaaS...       │ │ ➤  │        │
│  └──────────────────────────────────────────┘ └────┘        │
└──────────────────────────────────────────────────────────────┘
```

| Element | Description |
|---------|-------------|
| **Header** | "🤖 SaaSIQ AI Copilot" with Clear button |
| **Welcome message** | Initial greeting from the AI |
| **Suggestion chips** | 4 pre-built question buttons |
| **Chat area** | Scrollable conversation thread |
| **Input field** | Text input with send button (➤) |
| **Clear button** | Resets the conversation |

---

## Suggested Questions

Four clickable suggestion chips are shown before the first message:

| Chip | What it triggers |
|------|-----------------|
| **"Where can we save money?"** | Spend analysis with optimization suggestions |
| **"Show shadow IT apps"** | List of all unmanaged applications |
| **"Upcoming renewals"** | Renewal calendar with action items |
| **"What's our compliance risk?"** | Compliance summary with framework coverage |

> [!TIP]
> Chips disappear after you send your first message, but you can always type the same questions manually.

---

## Conversation Topics & Responses

### Topic 1: Spend Analysis

**User asks:** *"Where can we save money?"* or *"Analyze our SaaS spending"*

**AI Response:**

```
🤖 Here's your spend analysis:

📊 Total Monthly Spend: ₹42.5L across 156 applications

Top 3 Savings Opportunities:

┌─────────────────────────────────────────────────────────┐
│  1. Figma Enterprise                      Save ₹4.8L/mo │
│     57 unused licenses (29% utilization)                 │
│     → Downgrade inactive seats to Viewer                 │
│                                                          │
│  2. Slack Enterprise                      Save ₹3.2L/mo │
│     188 inactive users (62% utilization)                 │
│     → Remove unused seats or downgrade plan              │
│                                                          │
│  3. Jira + Asana + Monday.com             Save ₹2.8L/mo │
│     Overlapping project management tools                 │
│     → Consolidate to a single platform                   │
└─────────────────────────────────────────────────────────┘

💰 Total potential savings: ₹10.8L/month (₹1.3Cr/year)

Would you like me to:
• Generate a detailed report for any of these?
• Create an optimization plan?
• Show spend by department?
```

---

### Topic 2: Shadow IT

**User asks:** *"Show shadow IT apps"* or *"What unapproved tools are employees using?"*

**AI Response:**

```
🤖 I found 8 shadow IT applications:

⚠️ Shadow IT Summary:
• Total unapproved apps: 8
• Total exposed users: 248
• Estimated untracked cost: ₹2.8L/month

┌──────────────────────────────────────────────────────────┐
│  App            │ Users │ Risk     │ Est. Cost  │ Dept   │
│  ────────────── │ ───── │ ──────── │ ────────── │ ────── │
│  ChatGPT Plus   │ 67    │ Critical │ ₹80,400/mo │ Multi  │
│  Loom           │ 45    │ High     │ ₹54,000/mo │ Sales  │
│  Notion         │ 34    │ Medium   │ ₹40,800/mo │ Eng    │
│  Grammarly      │ 28    │ Low      │ ₹16,800/mo │ Mktg   │
│  Airtable       │ 22    │ High     │ ₹26,400/mo │ Ops    │
│  Linear         │ 19    │ Medium   │ ₹22,800/mo │ Eng    │
│  Canva Pro      │ 18    │ Low      │ ₹21,600/mo │ Mktg   │
│  Miro           │ 15    │ Low      │ ₹18,000/mo │ Design │
└──────────────────────────────────────────────────────────┘

🔴 Priority: ChatGPT Plus (Critical risk — 67 users may be
   pasting sensitive data into an AI tool without DPA)

Recommended actions:
1. Block ChatGPT Plus → suggest Microsoft Copilot
2. Review Loom + Airtable (High risk)
3. Evaluate Notion + Linear for official adoption

Go to SaaS Discovery to take action →
```

---

### Topic 3: Renewals

**User asks:** *"Upcoming renewals"* or *"What contracts are expiring soon?"*

**AI Response:**

```
🤖 Here are your upcoming renewals:

📅 Next 90 Days — 5 renewals totaling ₹92.3L/year

┌──────────────────────────────────────────────────────────┐
│  App            │ Date       │ Annual   │ Status         │
│  ────────────── │ ────────── │ ──────── │ ────────────── │
│  Slack          │ Mar 15     │ ₹18.0L   │ ⚠️ 7 days!     │
│  Salesforce     │ Apr  1     │ ₹24.0L   │ 🟡 24 days     │
│  AWS            │ Apr 15     │ ₹36.0L   │ 🟢 38 days     │
│  Figma          │ May  1     │ ₹8.4L    │ 🟢 54 days     │
│  Notion         │ May 20     │ ₹4.9L    │ 🟢 73 days     │
└──────────────────────────────────────────────────────────┘

⚡ Urgent: Slack renewal is in 7 days!
   Recommendation: Negotiate before auto-renewal.
   You can save ~₹3.6L/yr based on current utilization (62%).
   AI negotiation brief is ready.

Would you like me to:
• Generate a negotiation brief for Slack?
• Set reminders for each renewal?
• Show the full 12-month renewal calendar?
```

---

### Topic 4: Compliance

**User asks:** *"What's our compliance risk?"* or *"Show compliance status"*

**AI Response:**

```
🤖 Here's your compliance overview:

🛡️ Overall Risk Grade: B+ (78/100)

Framework Coverage:
• SOC 2 Type II:  ████████░░ 85%  — 3 apps non-compliant
• GDPR:           █████████░ 91%  — 2 apps missing DPA
• HIPAA:          ███████░░░ 72%  — 5 apps need BAA
• ISO 27001:      ██████░░░░ 68%  — 7 apps not certified

🔴 High-Risk Applications (Immediate Attention):
1. ChatGPT Plus — Shadow IT, no DPA, data training risk
2. Loom — No SOC 2, data stored outside India
3. Airtable — Expired SOC 2, no BAA

📋 Top 3 Remediation Steps:
1. Block ChatGPT Plus (Critical risk, 67 users)
2. Request updated SOC 2 from Airtable
3. Add DPA agreements for 2 GDPR-flagged apps

Implementing these 3 steps would raise your score to A- (87/100).

Go to Compliance & Risk for detailed remediation →
```

---

### Topic 5: Usage

**User asks:** *"Which apps have the lowest utilization?"* or *"Show usage data"*

**AI Response:**

```
🤖 Here's your usage analysis:

📊 Average Utilization: 67% across 156 apps
🔴 847 unused individual licenses detected

Most Underutilized Applications:
┌──────────────────────────────────────────────────────────┐
│  App            │ Licensed │ Active │ Util.  │ Waste/mo  │
│  ────────────── │ ──────── │ ────── │ ────── │ ───────── │
│  Figma          │ 80       │ 23     │  29% 🔴│ ₹4.8L     │
│  LinkedIn Nav.  │ 60       │ 27     │  45% 🔴│ ₹1.6L     │
│  Adobe CC       │ 40       │ 15     │  38% 🔴│ ₹1.5L     │
│  Miro           │ 50       │ 26     │  52% 🟠│ ₹0.8L     │
│  Slack          │ 500      │ 312    │  62% 🟠│ ₹3.2L     │
└──────────────────────────────────────────────────────────┘

💰 Reclaiming all unused licenses would save ₹11.9L/month

🏆 Best utilized apps:
1. Google Workspace: 96% ✅
2. GitHub Enterprise: 78% 🟡
3. Jira: 74% 🟡

Would you like me to:
• Generate a license reclamation plan?
• Show usage trends over the last 6 months?
• Break down usage by department?
```

---

### Default Response (Unrecognized Query)

**User asks:** *Anything not matching the above topics*

**AI Response:**

```
🤖 I can help you with:

• 💰 Spend Analysis — "Where can we save money?"
• 🔍 Shadow IT — "Show unapproved apps"
• 📅 Renewals — "What's coming up for renewal?"
• 🛡️ Compliance — "What's our compliance status?"
• 📊 Usage — "Which apps are underutilized?"

Try asking one of these, or click a suggestion above!
```

---

## How to Use Effectively

### Power User Tips

<details>
<summary><strong>💡 Ask specific, data-driven questions</strong></summary>

Instead of: *"Tell me about our apps"*
Ask: *"Which apps in Engineering have less than 50% utilization?"*

Instead of: *"How are we doing?"*
Ask: *"What's our compliance score and what are the top 3 gaps?"*

Specific questions get specific, actionable answers.

</details>

<details>
<summary><strong>💡 Follow up for deeper analysis</strong></summary>

After getting a spend analysis, follow up with:
- *"Show me just the Engineering spend breakdown"*
- *"Generate an optimization plan for the top 3 savings"*
- *"How does our Slack spend compare to industry benchmarks?"*

The Copilot maintains conversation context within a session.

</details>

<details>
<summary><strong>💡 Use Copilot for meeting preparation</strong></summary>

Before a budget review: *"Summarize our SaaS spend trends for the last quarter"*
Before a vendor call: *"Generate a negotiation brief for Salesforce"*
Before a security audit: *"What compliance gaps do we need to fix before our SOC 2 audit?"*

</details>

### Common Workflows

| I want to… | Ask the Copilot |
|------------|----------------|
| Prepare for budget meeting | *"Summarize our SaaS spend and top savings opportunities"* |
| Investigate shadow IT | *"Show all unapproved apps sorted by risk"* |
| Plan for upcoming renewals | *"What renewals are coming in the next 60 days?"* |
| Audit compliance posture | *"What's our compliance risk score and biggest gaps?"* |
| Find license waste | *"Which apps have the most unused licenses?"* |
| Compare vendor pricing | *"How does our Salesforce pricing compare to benchmarks?"* |

---

## Validation Checklist

### Interface
- [ ] Chat interface loads with welcome message
- [ ] 4 suggestion chips visible before first message
- [ ] Input field accepts text
- [ ] Send button (➤) is clickable
- [ ] Clear button resets conversation

### Suggestion Chips
- [ ] "Where can we save money?" triggers spend response
- [ ] "Show shadow IT apps" triggers shadow IT response
- [ ] "Upcoming renewals" triggers renewals response
- [ ] "What's our compliance risk?" triggers compliance response
- [ ] Chips disappear after first message

### Responses
- [ ] Each topic produces a structured, data-rich response
- [ ] Response includes tables with real data
- [ ] Response includes follow-up suggestions
- [ ] Links to relevant pages work
- [ ] Typing indicator shows while AI "thinks"
- [ ] Response appears in chat bubble format

### Conversation
- [ ] Multiple messages can be sent in sequence
- [ ] Previous messages remain visible in chat
- [ ] Scrolling works for long conversations
- [ ] Unrecognized queries show the help menu
- [ ] Clear button resets to welcome state

---

## Related Resources

- 🔗 [AI Insights](ai-insights.md) — Proactive recommendations (push model)
- 🔗 [Spend Intelligence](../intelligence/spend-intelligence.md) — Detailed cost data
- 🔗 [SaaS Discovery](../intelligence/saas-discovery.md) — App inventory
- 🔗 [Compliance & Risk](../governance/compliance-and-risk.md) — Compliance framework details
- 🔗 [Renewals](../operations/renewals.md) — Renewal management

---

---

<div align="center">

**Was this page helpful?** 👍 Yes · 👎 No · [Suggest an edit](https://github.com/saasiq/saasiq-documentation/edit/main/docs/ai-features/ai-copilot.md)

---

<a href="ai-insights.md">⬅️ AI Insights</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="../operations/index.md">Operations Module ➡️</a>

<sub>Last updated: March 2026 · SaaSIQ Documentation v1.0.0</sub>

</div>
