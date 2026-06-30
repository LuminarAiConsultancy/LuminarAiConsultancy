## Hi, I'm Joy 👋

I work on **responsible AI and decision governance** for leaders who have to answer for outcomes. Most of my work is with Canadian public-sector organizations, NGOs, and regulated bodies preparing for AI adoption.

I'm a governance practitioner who also ships the code. That combination shapes everything here: tools built by someone who has sat in the room when an AI decision goes wrong and had to explain it.

### What I'm building: LUMINARYX

A multi-tenant SaaS platform that helps Canadian municipalities adopt AI responsibly — the governance, audit, and accountability layer that lets a public body actually defend its AI decisions. Sole architect and engineer.

The hard parts, and how it's built:

- **Multi-tenant from the ground up** — strict tenant isolation, per-tenant provisioning, and an isolation audit layer so one municipality's data can never bleed into another's.
- **Tamper-evident audit trails** — hash-chained, HMAC-signed records. Every governance decision is append-only and verifiable, because the whole product is about defensibility.
- **Fail-closed security** — authentication that denies by default rather than failing open. If the auth layer can't verify, nobody gets in.
- **Built for regulated reality** — bilingual EN/FR throughout, seven Canadian regulatory frameworks encoded as structured requirements, approval workflows, board-pack PDF generation, and a contractor portal.
- **Production-grade plumbing** — Stripe billing, a full CI/CD pipeline, and an immutable, version-and-append data model so historical governance records can never be silently rewritten.

**Stack:** Python / FastAPI backend · React frontend · PostgreSQL · Redis · Docker · AWS (ca-central-1)

**Scale:** ~113K lines of application code · 200+ API endpoints · 87 React components · 39 database tables · 1,200+ tests in CI.

*(The codebase is private, but I'm happy to walk through the architecture.)*

### Also building

- 🏛️ **Municipal AI governance tooling** — practical infrastructure for small and mid-sized Canadian municipalities adopting AI responsibly
- 🔍 **Open-source gateways and guardrails** — PII scrubbing, audit trails, and policy enforcement that municipalities can actually run
- 📋 Governance frameworks grounded in **evidence over attestation, named accountability over passive voice**

### Pinned work

- **[municipal-ai-gateway](https://github.com/LuminarAiConsultancy/municipal-ai-gateway)** — open-source AI governance proxy gateway for Canadian municipalities. FastAPI + PostgreSQL, with live PII scrubbing for Canadian identifiers (SIN, PHN, postal codes, and more).

### Background

Over 30 years in business and tech operations, self-taught developer, and a sitting municipal councillor — so I've watched the gap between AI adoption and operational governance up close. I architected and shipped LUMINARYX solo, and I build for the people who have to defend the decision later.

---

📍 British Columbia, Canada
🔗 [LinkedIn](https://www.linkedin.com/in/joyguyot) · [LUMINARYX](https://luminaryx.ca)
