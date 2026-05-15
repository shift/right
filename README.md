# Deploy Day

> 📍 Late Game · 11 decisions made

You walk into the deployment bay. Screens everywhere. Red lines, green lines, dashboards nobody explained to you.

You're staring at the deployment pipeline. 47 stages. Everything passed CI. Staging looks good. Canary checks are configured.

It's 4:45pm. The deploy button waits.

The CEO's Slack status: "👀 watching the pipeline."

*Facebook's deployment process (before they were Meta): they deployed to production 3x per day. They could do this because every deploy went through canary analysis, automated rollback, and a "gatekeeper" system that would stop a deploy if error rates increased by even 0.1%. Speed requires safety. Safety enables speed.*

*[About this game →](https://github.com/shift/left/blob/main/credits/README.md)*

---

- [Deploy now, monitor closely](./deploy-now/README.md)
- [Wait for Monday morning](./monday-deploy/README.md)
- [Deploy on Friday, get it over with](./friday-deploy/README.md)
- [Configure the canary first — what % of traffic?](./canary-config/README.md)
- [What's the rollback plan?](./rollback-test/README.md)
- [Deploy behind a feature flag](./feature-flag/README.md)
- [Dark-launch to internal users first](./dark-launch/README.md)

*7 paths forward. Choose wisely — there is no going back.*

