# :shield: Governance Module

**Stay compliant, manage contracts, and enforce organizational policies.**

The Governance module ensures your SaaS portfolio is **secure, compliant, and contractually managed**. Three integrated features work together to protect your organization from risk while keeping vendor relationships under control.

<div class="grid-cards" markdown>

<a href="compliance-and-risk/" markdown>
<span class="card-icon">:white_check_mark:</span>
<span class="card-title">Compliance & Risk</span>
<span class="card-desc">Are our apps secure and compliant? Monitor frameworks, score vendor risk, and remediate issues.</span>
<span class="card-meta">B+ score (78/100) · SOC 2, GDPR, HIPAA, ISO 27001</span>
</a>

<a href="contracts/" markdown>
<span class="card-icon">:page_facing_up:</span>
<span class="card-title">Contracts</span>
<span class="card-desc">When do contracts expire? Track lifecycles, costs, and get AI negotiation help.</span>
<span class="card-meta">34 active · 8 renewing in 90 days</span>
</a>

<a href="policies/" markdown>
<span class="card-icon">:lock:</span>
<span class="card-title">Policies</span>
<span class="card-desc">What rules govern SaaS usage? Define spend limits, data residency, and security standards.</span>
<span class="card-meta">3 active policies · 2 violations this month</span>
</a>

</div>

---

## How These Features Connect

```mermaid
graph TD
    A["🛡️ Compliance & Risk"] -->|"Risk data informs"| B["📄 Contracts"]
    B -->|"Contract terms feed"| C["📋 Policies"]
    C -->|"Policies enforce"| A
    
    A -->|"High-risk apps flagged"| D["🔍 SaaS Discovery"]
    B -->|"Renewal dates feed"| E["🔄 Renewals"]
    C -->|"Policy violations trigger"| F["🔔 Alerts"]
```

**Governance lifecycle:**

1. **Compliance & Risk** scores each vendor's security posture
2. **Contracts** manages the commercial relationship and renewal timeline
3. **Policies** enforces organizational rules (spend limits, data residency, security standards)
4. Violations and risks trigger **Alerts** and inform **SaaS Discovery** decisions

---

## When to Use Each Feature

??? tip "Compliance & Risk — *Am I exposed to regulatory risk?*"

    **Use when:**

    - Preparing for an audit (SOC 2, ISO 27001, etc.)
    - Evaluating a new vendor's security posture
    - A data breach is reported for a vendor you use
    - You need to identify apps without DPA agreements

    **Go to:** [Compliance & Risk →](compliance-and-risk.md)

??? tip "Contracts — *What's coming up for renewal?*"

    **Use when:**

    - Reviewing the upcoming 30/60/90-day renewal pipeline
    - Preparing for a vendor negotiation
    - Checking if a contract is still within terms
    - Creating a renewal calendar for finance planning

    **Go to:** [Contracts →](contracts.md)

??? tip "Policies — *What rules does our org enforce?*"

    **Use when:**

    - Setting up SaaS governance rules for the first time
    - Defining spending thresholds that trigger approvals
    - Configuring data residency requirements
    - Creating security policies for vendor evaluation

    **Go to:** [Policies →](policies.md)

---

## Related Resources

- :link: [SaaS Discovery](../intelligence/saas-discovery.md) — Risk levels feed from Compliance data
- :link: [Renewals](../operations/renewals.md) — Operational renewal management
- :link: [Alerts & Notifications](../administration/alerts-notifications.md) — Policy violation alerts
