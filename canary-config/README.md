# The Canary Configuration

> 📍 Late Game · 12 decisions made

What percentage of traffic to route to the new version?

1% is barely measurable. 5% catches most issues. 25% catches everything but affects a lot of users if it's wrong. 100% is not a canary — it's just a deploy with extra steps.

*Netflix's Chaos Monkey randomly kills production instances to test resilience. Their canary deployments route 1% of traffic and measure 47 different metrics before proceeding. If any metric degrades, the canary fails automatically. No human judgment required. The system protects itself.*

---

- [5% canary, 30-minute observation](../monitoring/README.md)
- [25% canary, 15-minute observation](../canary/25-percent/README.md)
- [Fine, 100% — the CEO wants it live](../deploy-now/README.md)

**3 choices — there is no going back.**

