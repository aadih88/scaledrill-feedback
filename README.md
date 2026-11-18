# ScaleDrill — Public Feedback & Scenario Tracker

**ScaleDrill** is a 5-minute daily production outage simulator where engineers diagnose real-world distributed systems failures using SQL and deploy architectural fixes under a strict SLA clock and cloud budget.

> **Play the daily drill:** [scaledrill.com](https://your-production-domain.com) *(replace with your Vercel URL once deployed)*

---

### Why This Repository Exists
To keep upcoming daily incidents spoiler-free and protect puzzle integrity, ScaleDrill's application source code is maintained in a private repository. This public repository serves as our community hub for bug reports, UX feedback, and new outage scenario proposals.

### How to Contribute
* **[Report a Bug or UI Issue](https://github.com/aadih88/scaledrill-feedback/issues/new?labels=bug):** Include the Incident ID (e.g., `SD-RES-01` or `2026-11-18`), your browser/device (e.g., Chrome on Android `360px` or Firefox on Linux), and steps to reproduce.
* **[Propose a New Outage Scenario](https://github.com/aadih88/scaledrill-feedback/issues/new?labels=scenario-idea):** Share a real-world failure mode (e.g., connection pool exhaustion, thundering herd, split-brain cache, cascading retries), key symptom metrics, and the root cause mechanism.
* **[Request a Feature or UX Improvement](https://github.com/aadih88/scaledrill-feedback/issues/new?labels=enhancement):** Let us know what would make the SQL investigation or post-mortem experience sharper.

### Spoiler Etiquette
Please avoid putting root-cause answers or remediation solutions in **issue titles** so other players browsing open issues don't get spoiled on today's drill.
