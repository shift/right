# Deploy Day

> 📍 Late Game · 10 decisions made

You're staring at the deployment pipeline. 47 stages. Everything passed CI. Staging looks good. Canary checks are configured.

It's 4:45pm. The deploy button waits.

The CEO's Slack status: "👀 watching the pipeline."

*Facebook's deployment process (before they were Meta): they deployed to production 3x per day. They could do this because every deploy went through canary analysis, automated rollback, and a "gatekeeper" system that would stop a deploy if error rates increased by even 0.1%. Speed requires safety. Safety enables speed.*

---

- [Deploy now, monitor closely](./deploy-now)
- [Wait for Monday morning](./monday-deploy)
- [Deploy on Friday, get it over with](./friday-deploy)
- [Configure the canary first — what % of traffic?](./canary-config)
- [What's the rollback plan?](./rollback-test)
- [Deploy behind a feature flag](./feature-flag)
- [Dark-launch to internal users first](./dark-launch)
