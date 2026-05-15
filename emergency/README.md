# Emergency Deploy

> 📍 Late Game · 10 decisions made · 🔴 Danger

You revert. The payment service recovers. But the revert wasn't clean — the database migration is still there.

*The GitLab restoration saga: when their database was deleted, the restoration required coordinating backups from 5 different systems. The recovery was a 17-hour process. The post-mortem recommendation: every migration must have a tested rollback. Every. Single. One.*

---

- [Write a rollback script, test it in staging](../README.md)
- [Run the rollback directly in production](./raw-rollback/README.md)

**2 choices — there is no going back.**

