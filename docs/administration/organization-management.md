<div align="center" markdown>

<img src="https://img.shields.io/badge/Module-Administration-D97706?style=for-the-badge&logo=wrench&logoColor=white" alt="Administration" />
<img src="https://img.shields.io/badge/Feature-Org%20Management-blue?style=for-the-badge&logo=building&logoColor=white" alt="Organization Management" />

# 🏢 Organization Management

**Multi-org switching, user profiles, help center, and keyboard shortcuts**

`Home` · `Administration` · **Organization Management**

</div>

---

## Overview

Organization Management handles **multi-org support** (for companies managing multiple entities), the **user profile** menu, the **help center**, and **keyboard shortcuts**. These are global features accessible from the top bar on every page.

---

## In This Article

- [Organization Switcher](#organization-switcher)
- [User Profile Menu](#user-profile-menu)
- [Help Center](#help-center)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Validation Checklist](#validation-checklist)

---

## Organization Switcher

**Access:** Click the **🏢 org name** in the top bar

<table markdown>
<tr markdown><th align="left">🏢 Your Organizations</th></tr>
<tr markdown><td markdown>

✅ **TechCorp India** <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Business Plan · Admin

○ &nbsp; **TechCorp US** <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Business Plan · Manager

○ &nbsp; **Acme Corp** (Client) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Starter Plan · Viewer

</td></tr>
<tr markdown><td markdown>

`+ Create Organization` &nbsp; `Manage Organizations`

</td></tr>
</table>

**Interactions:**

| Action | Result |
|--------|--------|
| Click another org | Switches to that org — dashboard reloads with its data |
| Click **"+ Create Organization"** | Opens new org creation form |
| Click **"Manage Organizations"** | Opens admin panel for org settings |

### Create Organization Modal

| Field | Type | Required |
|-------|------|----------|
| **Organization Name** | Text | ✅ |
| **Industry** | Dropdown | ✅ |
| **Company Size** | Dropdown | ✅ |
| **Region** | Dropdown | ✅ |
| **Currency** | Dropdown | ✅ |
| **Invite initial admin** | Email | Optional |

!!! tip
    Create separate organizations for distinct business units or subsidiaries that have independent SaaS portfolios. Use a single org if all departments share the same tools.

---

## User Profile Menu

**Access:** Click the **👤 avatar** in the top bar

<table markdown>
<tr markdown><td markdown>

**👤 Rahul Sharma** <br />
rahul@techcorp.in <br />
Admin · TechCorp India

</td></tr>
<tr markdown><td markdown>

📝 Edit Profile <br />
❓ Help Center <br />
⌨️ Keyboard Shortcuts <br />
📋 Activity Log <br />
🚪 Logout

</td></tr>
</table>

### Edit Profile Modal

| Field | Value | Editable |
|-------|-------|----------|
| **Full Name** | Rahul Sharma | ✅ |
| **Email** | rahul@techcorp.in | ❌ (contact admin) |
| **Avatar** | Upload area | ✅ |
| **Job Title** | IT Manager | ✅ |
| **Department** | IT | ✅ |
| **Phone** | +91 98xxx xxxxx | ✅ |
| **Timezone** | Asia/Kolkata | ✅ |

### Activity Log

Shows a chronological log of your recent actions:

| Time | Action | Details |
|------|--------|---------|
| 10:32 AM | Approved app | Notion → Managed |
| 10:15 AM | Viewed report | Compliance & Risk |
| 09:45 AM | Applied optimization | Figma license downgrade |
| 09:30 AM | Logged in | via Google SSO |

### Logout

- Click **"Logout"** → confirmation: "Are you sure you want to sign out?"
- Confirm → session cleared → redirected to Login page

---

## Help Center

**Access:** Profile menu → **"❓ Help Center"**

| Section | Content |
|---------|---------|
| **Getting Started** | Links to Quick Start Guide, Onboarding |
| **Feature Guides** | Links to each module's documentation |
| **Video Tutorials** | Embedded placeholder videos for key workflows |
| **Contact Support** | Email (support@saasiq.io), live chat toggle |
| **System Status** | Link to status page |
| **What's New** | Changelog of recent updates |

---

## Keyboard Shortcuts

**Access:** Profile menu → **"⌨️ Keyboard Shortcuts"** or press `?`

| Shortcut | Action |
|----------|--------|
| `⌘ + K` / `Ctrl + K` | Open global search |
| `⌘ + /` / `Ctrl + /` | Open AI Copilot |
| `G then D` | Go to Dashboard |
| `G then S` | Go to SaaS Discovery |
| `G then I` | Go to Spend Intelligence |
| `G then C` | Go to Compliance |
| `G then R` | Go to Renewals |
| `G then A` | Go to Alerts |
| `?` | Show keyboard shortcuts |
| `Escape` | Close any open modal/panel |

!!! tip
    The `G then X` pattern means press `G`, release, then press the second key. This is called a **key chord** and works anywhere in the app.

---

## Validation Checklist

- [ ] Org switcher dropdown opens from top bar
- [ ] Current org shows ✅ checkmark
- [ ] Switching orgs reloads the dashboard
- [ ] "Create Organization" opens form modal
- [ ] All creation fields work and validate
- [ ] User profile dropdown shows name, email, role
- [ ] "Edit Profile" opens modal with editable fields
- [ ] Avatar upload works
- [ ] "Activity Log" shows recent actions
- [ ] "Logout" clears session and redirects
- [ ] Help Center opens with all sections
- [ ] Keyboard shortcuts modal opens with `?`
- [ ] Key shortcuts navigate correctly (G+D, G+S, etc.)
- [ ] `⌘+K` opens global search
- [ ] `Escape` closes open modals

---

## Related Resources

- 🔗 [Settings](settings.md) — Organization and team configuration
- 🔗 [Keyboard Shortcuts](../reference/keyboard-shortcuts.md) — Complete shortcut reference
- 🔗 [FAQ](../reference/faq.md) — Frequently asked questions

---

---

<div align="center" markdown>

**Was this page helpful?** 👍 Yes · 👎 No · [Suggest an edit](https://github.com/saasiq/saasiq-documentation/edit/main/docs/administration/organization-management.md)

---

<a href="settings.md">⬅️ Settings</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="../reference/glossary.md">Glossary ➡️</a>

<sub>Last updated: March 2026 · SaaSIQ Documentation v1.0.0</sub>

</div>
