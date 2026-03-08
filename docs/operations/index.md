# :gear: Operations Module

**Day-to-day SaaS lifecycle management — offboarding, renewals, benchmarks, and costs.**

The Operations module is where **action gets taken**. From offboarding employees to managing renewals, benchmarking your spend, and analyzing department costs.

<div class="grid-cards" markdown>

<a href="offboarding/" markdown>
<span class="card-icon">:door:</span>
<span class="card-title">Offboarding</span>
<span class="card-desc">How do we ensure ex-employees lose all access? Automated license revocation synced with HR.</span>
<span class="card-meta">8 pending · 45 completed · 3 overdue</span>
</a>

<a href="renewals/" markdown>
<span class="card-icon">:calendar:</span>
<span class="card-title">Renewals</span>
<span class="card-desc">What's renewing soon? 30/60/90-day pipeline with AI-powered negotiation assistance.</span>
<span class="card-meta">₹12.8L savings YTD · 8 renewals in 90 days</span>
</a>

<a href="benchmarks/" markdown>
<span class="card-icon">:scales:</span>
<span class="card-title">Benchmarks</span>
<span class="card-desc">Are we paying more than we should? Compare pricing against industry peers for negotiation leverage.</span>
<span class="card-meta">6 vendors benchmarked · 3 overpriced</span>
</a>

<a href="department-costs/" markdown>
<span class="card-icon">:office:</span>
<span class="card-title">Department Costs</span>
<span class="card-desc">Which department is spending the most? Per-department breakdown with waste identification.</span>
<span class="card-meta">6 departments · ₹7L waste identified</span>
</a>

</div>

---

## How These Features Connect

```mermaid
graph TD
    A["👤 Offboarding"] -->|"Licenses freed"| B["💰 Department Costs"]
    C["🔄 Renewals"] -->|"Negotiation data"| D["📊 Benchmarks"]
    D -->|"Pricing intelligence"| C
    B -->|"Waste identified"| E["💡 Spend Intelligence"]
    A -->|"Seats reclaimed"| E
```

**Typical operational cycle:**

1. **Offboarding** recovers licenses when employees leave
2. **Renewals** surface upcoming contracts to review before auto-renewal
3. **Benchmarks** provide industry data to negotiate better pricing
4. **Department Costs** show where spend is going and where waste exists

---

## Related Resources

- :link: [Spend Intelligence](../intelligence/spend-intelligence.md) — Cost optimization recommendations
- :link: [Usage Analytics](../intelligence/usage-analytics.md) — License utilization data
- :link: [Contracts](../governance/contracts.md) — Contract detail view
