# The Canary Configuration

> 📍 Late Game · 11 decisions made

What percentage of traffic to route to the new version?

1% is barely measurable. 5% catches most issues. 25% catches everything but affects a lot of users if it's wrong. 100% is not a canary — it's just a deploy with extra steps.

*Netflix's Chaos Monkey randomly kills production instances to test resilience. Their canary deployments route 1% of traffic and measure 47 different metrics before proceeding. If any metric degrades, the canary fails automatically. No human judgment required. The system protects itself.*

---

- [5% canary, 30-minute observation](../deploy-now)
- [25% canary, 15-minute observation](../deploy-now)
- [Fine, 100% — the CEO wants it live](../deploy-now)

**3 choices — there is no going back.**

