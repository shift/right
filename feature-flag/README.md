# The Feature Flag Dilemma

> 📍 Late Game · 11 decisions made

The feature is behind a flag. You can deploy without enabling. Safe. Incremental.

But the CEO wants it live for the demo. If you deploy with the flag off, you can flip it during the demo. If something goes wrong, flip it off.

Unless "off" doesn't mean "off" for every user.

*Facebook's 2021 outage lasted 6 hours. The cause: a BGP configuration change that disconnected their backbone from the internet. The fix required physical access to the data center. But the outage also broke their badge readers. They couldn't get in. The feature flag (BGP) had no manual override. When your off switch requires the system to be on, you don't have an off switch.*

---

- [Deploy with flag off, enable during demo](../deploy-now)
- [Test the flag thoroughly before deploying](../sunday-deploy)
- [Skip the flag, deploy directly](../friday-deploy)

**3 choices — there is no going back.**

