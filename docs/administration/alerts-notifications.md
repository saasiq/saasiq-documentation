<div align="center" markdown>

<img src="https://img.shields.io/badge/Module-Administration-D97706?style=for-the-badge&logo=wrench&logoColor=white" alt="Administration" />
<img src="https://img.shields.io/badge/Feature-Alerts-blue?style=for-the-badge&logo=bell&logoColor=white" alt="Alerts" />
<img src="https://img.shields.io/badge/Updated-March_2026-green?style=for-the-badge&logo=calendar&logoColor=white" alt="Updated" />

# 🔔 Alerts & Notifications

**Real-time alert feed with severity levels, snooze controls, and notification preferences**

`Home` · `Administration` · **Alerts & Notifications**

</div>

---

## Overview

The Alerts system is SaaSIQ's **real-time notification engine**. It surfaces critical events — shadow IT detections, spending spikes, compliance violations, renewal reminders, and AI recommendations — through an in-app alert panel, with optional email and Slack integrations.

---

## In This Article

- [Alert Panel](#alert-panel)
- [Alert Types & Severity](#alert-types-severity)
- [Operations: Snooze, Dismiss, Configure](#operations)
- [Alert Settings](#alert-settings)
- [Validation Checklist](#validation-checklist)

---

## Alert Panel

**Access:** Click the 🔔 notification bell in the top bar

<table markdown>
<tr markdown>
<td markdown>

**🔔 Alerts** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `Mark All Read`

</td>
</tr>
<tr markdown>
<td markdown>

🔴 **CRITICAL** · 2 hours ago

3 new shadow IT apps discovered — ChatGPT Plus, Loom, Notion detected in Engineering and Sales departments

`Review in Discovery` &nbsp; `Snooze` &nbsp; `Dismiss`

</td>
</tr>
<tr markdown>
<td markdown>

🟡 **WARNING** · 5 hours ago

Slack renewal in 7 days — ₹18L contract. Auto-renewal will trigger if no action taken

`Review Renewal` &nbsp; `Snooze` &nbsp; `Dismiss`

</td>
</tr>
<tr markdown>
<td markdown>

🟣 **AI INSIGHT** · 8 hours ago

New savings opportunity: ₹4.8L/month — Figma license optimization identified

`View Insight` &nbsp; `Snooze` &nbsp; `Dismiss`

</td>
</tr>
<tr markdown>
<td markdown>

🔵 **INFO** · 1 day ago

Monthly compliance report available — Risk score improved: B → B+

`View Report` &nbsp; `Dismiss`

</td>
</tr>
</table>

---

## Alert Types & Severity

| Severity | Color | Icon | Example | Default Delivery |
|----------|-------|------|---------|-----------------|
| **Critical** | 🔴 Red | ⚠️ | Shadow IT detected, security breach | In-app + Email + Slack |
| **Warning** | 🟡 Yellow | ⚡ | Renewal upcoming, utilization drop | In-app + Email |
| **AI Insight** | 🟣 Purple | 🤖 | New optimization, prediction | In-app only |
| **Info** | 🔵 Blue | ℹ️ | Report ready, sync complete | In-app only |

---

## Operations

### Snooze Alert

**Trigger:** Click **"Snooze"** on any alert

| Option | Duration |
|--------|---------|
| 1 hour | Quick snooze |
| 4 hours | Half-day |
| 24 hours | Full day |
| 1 week | Extended |
| Custom | Pick date/time |

**Behavior:**
- Alert disappears from the panel for the selected duration
- Returns to the panel when snooze expires
- Badge count decreases while snoozed

### Mark All Read

- Clears the unread indicator on all alerts
- Badge count on 🔔 resets to 0
- Alerts remain in the panel but appear as read (lighter styling)

### Dismiss

- Permanently removes the alert from the panel
- Does NOT resolve the underlying issue
- Cannot be undone

!!! warning
    Dismissing a Critical alert without acting on it creates a security gap. Use Snooze if you need time, Dismiss only after resolving.

---

## Alert Settings

**Access:** Click **"⚙️ Alert Settings"** at the bottom of the alert panel

| Setting | Options | Default |
|---------|---------|---------|
| **Shadow IT Detection** | On / Off | ✅ On |
| **Renewal Reminders** | Off / 7d / 14d / 30d / 60d | 30d |
| **Spending Alerts** | Off / >₹1L / >₹5L / >₹10L | >₹1L |
| **Compliance Violations** | On / Off | ✅ On |
| **AI Recommendations** | On / Off | ✅ On |
| **Usage Drops** | Off / >10% / >20% / >30% | >20% |

| Delivery Channel | Options |
|-----------------|---------|
| **In-app** | Always on (cannot disable) |
| **Email** | Toggle per severity level |
| **Slack Integration** | Toggle per severity level (requires Slack in Settings) |

---

## Validation Checklist

- [ ] Bell icon shows unread count badge
- [ ] Clicking bell opens alert panel  
- [ ] Alerts appear with correct severity colors
- [ ] "Review in Discovery" navigates correctly
- [ ] "Review Renewal" navigates correctly
- [ ] "View Insight" navigates correctly
- [ ] Snooze hides alert for selected duration
- [ ] "Mark All Read" clears badge and marks all read
- [ ] Dismiss removes alert from panel
- [ ] Alert Settings opens configuration modal
- [ ] All 6 toggles are functional
- [ ] Delivery channel toggles work

---

## Related Resources

- 🔗 [Settings](settings.md) — Configure integration channels (Slack, email)
- 🔗 [Policies](../governance/policies.md) — Policies that generate violation alerts
- 🔗 [SaaS Discovery](../intelligence/saas-discovery.md) — Shadow IT alert source
- 🔗 [Renewals](../operations/renewals.md) — Renewal reminder source

---

---

<div align="center" markdown>

**Was this page helpful?** 👍 Yes · 👎 No · [Suggest an edit](https://github.com/saasiq/saasiq-documentation/edit/main/docs/administration/alerts-notifications.md)

---

<a href="index.md">⬅️ Administration Overview</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="settings.md">Settings ➡️</a>

<sub>Last updated: March 2026 · SaaSIQ Documentation v1.0.0</sub>

</div>
