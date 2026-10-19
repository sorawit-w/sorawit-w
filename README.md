### Hi, I'm Kiang 👋

Full-stack engineer in Torrance, CA. Fifteen-plus years building shared infrastructure, design systems, and developer tools — the kind of work where the deliverable isn't a feature, it's the platform other engineers depend on.

Lately I've been thinking about a narrower problem: how to make AI agents do reliable work. Not by making the model better — by designing the harness around it so the rules actually land.

---

**What I'm building**

- **[kerby](https://github.com/sorawit-w/kerby)** — an AI agent governance harness. A GATE → WEIGH → VERDICT loop that makes rules land at decision time, not just live in a doc. Three-token verdicts: PASS / DENIED / HELD.
- **[agent-skills](https://github.com/sorawit-w/agent-skills)** — a shelf of opinionated Claude Code plugins — each one narrow, each evaluated before it ships. Treats skill authoring as harness engineering — context, scaffolding, feedback loops, state, eval discipline *around* the agent.
- **[job-scout](https://github.com/sorawit-w/job-scout)** — an agent skill that finds open jobs that fit your resume, read straight from employer job boards (Greenhouse, Ashby, Lever, SmartRecruiters, Workday). Nothing is searched until you confirm the brief, and every fit reason is quoted from the posting and checked by a script. Standard-library Python, ~14,000 verified boards.
- **[declair.ai](https://declair.ai)** — decision-clarity platform built solo end-to-end. Pairwise comparison, Condorcet aggregation, real-time SSE, 20-locale i18n. SvelteKit · Elysia/Bun · PostgreSQL.
- **[konthai](https://github.com/sorawit-w/konthai)** — decodes deliberately mangled Thai (สก๊อย glyph swaps, ciphers, spoonerisms) back to standard Thai + English. A parser for the messiest real-world input I could find.

**Day job**

Lead Software Engineer at Parcel Pro (a UPS company). Design system, BFF layer, and CI/CD pipeline behind customer-facing insurance products.

---

**How I think about the work**

- *Trust is an emergent property of system design,* not a UI detail.
- Rules must land, not just exist — if they don't survive realistic prompts, they're decoration.
- Configuration over hard-coding. Reversible decisions over irreversible ones.
- Boring and readable beats clever. Other engineers should be able to depend on the code.

---

**Find me**

- 🌐 [sorawit.com](https://sorawit.com) · 💼 [LinkedIn](https://www.linkedin.com/in/sorawit-w/) · 📬 <hi@sorawit.com>
