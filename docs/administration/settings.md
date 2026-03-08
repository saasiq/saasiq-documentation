# ⚙️ Settings

**Complete platform configuration — organization, integrations, team, security, and billing**

> **Home** · Administration · **Settings**

---

## Overview

Settings is the comprehensive configuration hub for SaaSIQ. It's organized into **8 sub-tabs**, each controlling a different aspect of the platform. Only users with **Admin** role can modify settings; Managers and Viewers have read-only access.

---

## Settings Navigation

<table markdown>
<tr markdown>
<td width="180" valign="top" markdown>

**Navigation** <br /><br />
🏢 Organization <br />
🔗 Integrations <br />
👥 Team Members <br />
🔔 Notifications <br />
🔒 Security <br />
🎨 Appearance <br />
🔌 API & Webhooks <br />
💳 Billing

</td>
<td valign="top" markdown>

**Content Area** <br /><br />
The selected tab's settings load here. The active tab shows a purple `#7C3AED` indicator on the left.

</td>
</tr>
</table>

Click any tab to load its content in the right panel. Active tab shows a purple indicator.

---

## Organization

| Field | Value (Demo) | Editable | Description |
|-------|-------------|----------|-------------|
| **Company Name** | TechCorp India | ✅ | Organization display name |
| **Industry** | Technology | ✅ | Used for benchmarking |
| **Company Size** | 201–500 | ✅ | Employee count range |
| **Region** | India | ✅ | Primary operating region |
| **Timezone** | Asia/Kolkata (IST) | ✅ | Used for alert scheduling and reports |
| **Currency** | INR (₹) | ✅ | Default currency for all spend data |
| **Logo** | Upload area | ✅ | Company logo displayed in reports |
| **Contact Email** | admin@techcorp.in | ✅ | Primary admin contact |

**Actions:** `[Save Changes]` `[Reset to Default]`

---

## Integrations

Connected services that feed data into SaaSIQ.

| Integration | Status | Category | Data Provided |
|------------|--------|----------|---------------|
| **Google Workspace** | ✅ Connected | SSO | User directory, SSO logs, Drive activity |
| **Microsoft Entra ID** | ✅ Connected | SSO | User directory, sign-in logs |
| **Slack** | ✅ Connected | Communication | Workspace usage, app installations |
| **Jira** | ✅ Connected | Project Mgmt | Project activity, license usage |
| **AWS** | ⏸ Paused | Cloud | Service usage, cost data |
| **Salesforce** | ✅ Connected | CRM | License utilization, seat data |
| **GitHub** | ❌ Disconnected | Development | — |
| **Figma** | ✅ Connected | Design | Editor/viewer seats, project activity |
| **BambooHR** | ✅ Connected | HRIS | Employee directory, departure data |
| **QuickBooks** | ❌ Disconnected | Finance | — |

**Actions per integration:**

| Status | Available Actions |
|--------|------------------|
| ✅ Connected | [Pause] [Disconnect] [View Logs] [Refresh] |
| ⏸ Paused | [Resume] [Disconnect] |
| ❌ Disconnected | [Connect] |

<details markdown>
<summary><strong>🔧 How to connect a new integration</strong></summary>

1. Find the integration in the list → click **"Connect"**
2. An OAuth popup opens for the vendor
3. Grant the requested permissions (read-only by default)
4. On success: status changes to ✅ Connected
5. Initial sync begins automatically (may take 5–15 minutes)
6. Data starts appearing in Discovery, Usage, and Spend modules

</details>

!!! tip
    Pausing an integration preserves historical data but stops new data collection. Use this when troubleshooting or during vendor migrations.

---

## Team Members

| Name | Email | Role | Status | Last Active | Actions |
|------|-------|------|--------|------------|---------|
| Rahul Sharma | rahul@techcorp.in | Admin | ✅ Active | Today | [Edit] [—] |
| Anita Desai | anita@techcorp.in | Manager | ✅ Active | Yesterday | [Edit] [Remove] |
| Vikram Singh | vikram@techcorp.in | Viewer | ✅ Active | 3 days ago | [Edit] [Remove] |
| Priya Nair | priya@techcorp.in | Viewer | 📧 Invited | — | [Resend] [Remove] |

**Actions:**

| Button | Description |
|--------|-------------|
| **[+ Invite Member]** | Opens invite form (email + role selector) |
| **[Edit]** | Change member's role |
| **[Remove]** | Remove from organization (confirmation required) |
| **[Resend]** | Resend invitation email |

!!! warning
    Removing the last Admin will lock you out of Settings. Always maintain at least 2 Admin accounts.

---

## Notifications

Granular control over what notifications you receive and how.

| Event | In-App | Email | Slack | Default |
|-------|:------:|:-----:|:-----:|---------|
| Shadow IT detected | ✅ | ✅ | ✅ | All on |
| Renewal reminder | ✅ | ✅ | ❌ | Email + App |
| Spending threshold exceeded | ✅ | ✅ | ✅ | All on |
| Compliance violation | ✅ | ✅ | ❌ | Email + App |
| AI recommendation | ✅ | ❌ | ❌ | App only |
| Usage drop alert | ✅ | ❌ | ❌ | App only |
| Offboarding overdue | ✅ | ✅ | ✅ | All on |
| System updates | ✅ | ❌ | ❌ | App only |

Each row has toggles for each channel. Changes save automatically.

!!! tip
    Connect Slack in Integrations first to enable the Slack delivery channel.

---

## Security

| Setting | Description | Options |
|---------|-------------|---------|
| **Two-Factor Authentication** | Require 2FA for all users | ⬜ Off / ✅ Required |
| **Session Timeout** | Auto-logout after inactivity | 15min / 30min / 1hr / 4hr / Never |
| **IP Allowlist** | Restrict access to specific IPs | Text area for CIDR ranges |
| **SSO Enforcement** | Require SSO for all logins (no password login) | ⬜ Off / ✅ Required |
| **Audit Log Retention** | How long to keep audit logs | 30d / 90d / 1yr / Unlimited |
| **Data Export Restrictions** | Who can export data | All / Admins Only / Disabled |

**Actions:** `[Save Security Settings]` `[Download Audit Log]`

!!! important
    Enable 2FA and SSO Enforcement for maximum security. Set session timeout to 30 minutes for sensitive environments.

---

## Appearance

| Setting | Description | Options |
|---------|-------------|---------|
| **Theme** | Light or dark mode | 🌙 Dark (default) / ☀️ Light / 🖥 System |
| **Accent Color** | Primary UI color | Purple (default) / Blue / Green / Custom hex |
| **Compact Mode** | Reduce spacing for more data density | ⬜ Off / ✅ On |
| **Language** | Interface language | English (default) / Hindi |
| **Date Format** | How dates appear | DD/MM/YYYY / MM/DD/YYYY / YYYY-MM-DD |
| **Number Format** | Currency formatting | Indian (₹1,00,000) / International (₹100,000) |

---

## API & Webhooks

For developers and automation teams.

### API Keys

| Key Name | Created | Last Used | Status | Actions |
|----------|---------|----------|--------|---------|
| Production API | Jan 15, 2026 | Today | ✅ Active | [Rotate] [Revoke] |
| CI/CD Pipeline | Feb 1, 2026 | 2 days ago | ✅ Active | [Rotate] [Revoke] |

**Actions:** `[Generate New Key]` — creates a new API key with customizable scopes (Read All, Write, Admin).

### Webhooks

| Endpoint | Events | Status | Actions |
|---------|--------|--------|---------|
| `https://internal.techcorp.in/saasiq-hook` | All events | ✅ Active | [Edit] [Test] [Delete] |

**Actions:** `[Add Webhook]` — configure URL, select events (new app, spend alert, compliance violation, etc.), set secret for verification.

<details markdown>
<summary><strong>📡 API Quick Reference</strong></summary>

| Endpoint | Method | Description |
|---------|--------|-------------|
| `/api/v1/apps` | GET | List all discovered applications |
| `/api/v1/apps/:id` | GET | Get app details |
| `/api/v1/spend/summary` | GET | Get spend summary |
| `/api/v1/compliance/score` | GET | Get compliance risk score |
| `/api/v1/users` | GET | List team members |
| `/api/v1/alerts` | GET | List alerts |

All requests require `Authorization: Bearer <api_key>` header.

</details>

---

## Billing

| Field | Value (Demo) |
|-------|-------------|
| **Current Plan** | Business |
| **Billing Cycle** | Annual |
| **Next Invoice** | Apr 1, 2026 |
| **Amount** | ₹4,99,000/year |
| **Payment Method** | Visa ending 4242 |
| **Apps Included** | Unlimited |
| **Users Included** | Up to 500 |

**Plan comparison:**

| Feature | Starter (₹999/mo) | Business (₹2,499/mo) | Enterprise (Custom) |
|---------|:------------------:|:-------------------:|:------------------:|
| Discovered Apps | Up to 50 | Unlimited | Unlimited |
| Users | 5 | 25 | Unlimited |
| AI Copilot | ❌ | ✅ | ✅ |
| Custom Policies | 3 | 10 | Unlimited |
| API Access | ❌ | ✅ | ✅ |
| SSO | ❌ | ✅ | ✅ |
| Support | Email | Priority | Dedicated CSM |

**Actions:** `[Upgrade Plan]` `[Update Payment]` `[Download Invoice]` `[Cancel Subscription]`

---

## Validation Checklist

- [ ] Settings page loads with 8 tabs visible
- [ ] Organization tab shows all fields editable
- [ ] Integrations tab shows connected/disconnected states
- [ ] Connect/Disconnect/Pause/Resume actions work
- [ ] Team Members shows current members with roles
- [ ] Invite form accepts email and role
- [ ] Remove member shows confirmation
- [ ] Notification toggles save automatically
- [ ] Security settings save correctly
- [ ] Appearance theme toggle changes the UI
- [ ] API key generation works
- [ ] Webhook configuration accepts URL
- [ ] Billing shows plan details and invoice history

---

## Related Resources

- 🔗 [Onboarding Wizard](../getting-started/onboarding.md) — Initial configuration
- 🔗 [Alerts & Notifications](alerts-notifications.md) — Alert delivery settings
- 🔗 [Organization Management](organization-management.md) — Multi-org controls

---
