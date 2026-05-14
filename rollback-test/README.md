# The Rollback Plan

> 📍 Late Game · 11 decisions made

Before deploying, the senior engineer asks: "What's the rollback plan?"

The migration adds a column. The deploy changes three endpoints. If it fails, you need to revert code AND database. But the migration isn't reversible.

*The Google SRE Book's #1 deploy rule: "Every change must have a tested, verified rollback." Not a rollback plan. A tested rollback. Plans are hopes. Tests are evidence.*

---

- [Test the rollback in staging first](../deploy-now)
- [It'll be fine — ship it](../deploy-now)
