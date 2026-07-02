```yaml
title: "AI-First UX Practice — A Working System"
year: 2026
domain: Practice Development / AI-Augmented UX
duration: March 2026 — ongoing
primary_role: Practice Architect / AI Workflow Engineer
secondary_roles:
  - UX Strategist
  - Systems Designer
methods:
  - Agent architecture design
  - Workflow systems design
  - Automation engineering
  - Knowledge management
impact: A solo UX consultancy redesigned as an AI-first operation — with a permanent agent workforce, automated quality gates, and the throughput of a small team
```

# AI-First UX Practice — A Working System

| | |
|---|---|
| **5+** simultaneous client products in active delivery | **Full IA phase** — 6 deliverables produced by agent chain under human review |
| **45-minute** meeting transcript processed and logged in ~2 minutes | **24** cross-document inconsistencies caught by automated audit before client delivery |
| **38+** specialist agents and skills built and maintained | **13** reusable process templates codified from practice knowledge |

---

In early 2026, I stopped using AI as a productivity tool and started treating it as an organisational design problem.

The question was not "which tasks can AI do faster?" It was: what are the structural limits of a solo consultancy, and can AI remove them? A solo practitioner managing five concurrent client engagements faces constraints that no amount of personal efficiency resolves — context loss between sessions, sequential delivery where parallel would serve the client better, administrative work that crowds out thinking work, and quality checks that depend entirely on a single person's attention at the end of a long day. These are not efficiency problems. They are architectural problems. They required an architectural answer.

---

## The Agent Workforce

The centrepiece of the system is a **permanent AI workforce** — a structured roster of **specialist agents**, each with a defined identity, mandate, tools, and boundaries. The workforce is organised around a leadership layer and four departments.

**Sun Tzu** leads and orchestrates. He holds strategy, receives tasks from me, delegates to the four department leaders, and is responsible for outcomes. He does not author deliverables — his function is direction, routing, and synthesis.

**Jakob** leads the UX department. He covers the full UX practice: information architecture, heuristic evaluation, UX writing, accessibility analysis, and user research. When a complete IA phase is needed, Jakob runs it — producing content inventory, taxonomy, screen tree, navigation model, task-flow diagrams, and developer handoff.

**Tom** leads IT and process engineering. When a new task type arrives that has no established workflow, Tom researches it, designs the process, and documents it in a shared process library. More than twenty process templates now exist in that library, codified from what had previously been implicit, session-by-session re-explanation.

**Aristotle** leads research and holds the QA function. He provides evidence-based analysis grounded in domain expertise — UX, organisational design, cognitive science — rather than LLM generalisation. He also runs quality audits before delivery: reviewing deliverables against defined criteria, diagnosing failures by root cause, and routing fixes to the responsible agent. His most significant intervention to date: a cross-document audit across nine IA deliverables that surfaced twenty-four inconsistencies — five of them critical — caused by cross-reference drift after late-stage additions to the screen inventory. All were resolved before the client saw the work.

**Simon** manages the workforce itself. When a task requires a capability that doesn't yet exist, Simon creates the agent: names it, defines its mandate, writes its specification, and adds it to the roster. The workforce grows through use — every genuinely new task type can produce a new specialist.

Alongside the leadership layer, an independent advisor operates outside the department hierarchy: **Biblios** is the classical liberal arts advisor — consulted directly by any agent when a question requires philosophical depth, rhetorical precision, or historical grounding, and maintains the knowledge catalogue. Both are available to the entire workforce without routing through Sun Tzu. New agents are created by Simon when the work demands them, not speculatively in advance.

---

## The Practice Infrastructure

The agent workforce operates on top of a purpose-built practice infrastructure that solves the continuity problem.

Every client product has a dedicated repository. Within that repository, engagements are dated subfolders — but the product is the unit of continuity, not the engagement. When a new engagement begins on an existing product, all prior context is immediately available: previous research findings, stakeholder decisions, design system notes, open questions, and the full history of what was built and why. Nothing has to be reconstructed from memory or re-read from scratch. Client materials are processed locally within controlled, per-product workspaces and are never retained in shared or third-party systems — each client's data stays isolated to its own repository.

Each product uses a three-file system with strict separation of purpose. The project log is a design narrative — a running account of decisions, rationale, and outcomes, written as portfolio-source material after every session. The session file is operational housekeeping — a file index and a communications processing table that prevents duplication and ensures nothing is missed. The task file is a cross-product operational view, rebuilt daily by a cron job at 6 AM from the state of all active products.

Meeting transcripts and email threads enter the system through a drop-zone pipeline. A processing command reads each file, extracts decisions and action items, attributes them correctly, and logs them to the appropriate product's narrative. A forty-five-minute meeting transcript takes approximately two minutes to process. Across five concurrent products with weekly client contact, this eliminates what would otherwise be several hours of weekly administrative work — and more importantly, it eliminates the failure mode where a decision made in a meeting disappears before it reaches the relevant deliverable.

Finished deliverables — research reports, IA specifications, interaction models, acceptance criteria documents — are tracked in git and deployed to Cloudflare Pages in a single command. A prototype built in a session is shareable as a URL before the session ends.

---

## The Work Itself

The system is not a background operation running alongside the UX practice. It is the UX practice. The agents produce the deliverables. The infrastructure maintains the context. The quality layer reviews the output.

A complete information architecture phase for a mobile application — content inventory, taxonomy, screen tree, navigation model, five task-flow diagrams, and a developer handoff package — was produced by a specialist agent chain in a single session. No deliverable ships without human review and sign-off. My contribution was upstream and downstream: defining the brief, setting quality criteria, reviewing the output, approving or rejecting. The six deliverables were ready for client handoff at the end of the session.

Scope estimation works the same way. A 131-hour effort estimate across a mobile application and its admin panel — synthesised from a product requirements document, three meeting transcripts, and twelve email threads — was produced in one session, alongside forty-four scoped GitHub Issues with labels. The same task, done manually, would take two to three days.

Research and competitive analysis operate at a scale that was previously impractical. A full competitive landscape across twenty-seven agency targets in three geographies was researched, structured, and delivered in one session. A multi-locale UX audit of a live website across six locales — including the discovery that an entire locale had been inadvertently excluded from search engine indexing — was completed in a single session. An acceptance criteria document was translated from developer-facing technical specification to client-facing business proposal, in binding measurable language, in one session. These are not faster versions of existing tasks. They are categories of work that were structurally infeasible for a solo practitioner before the system existed.

---

## What This Means for a Client

A client engaging Faber-Ludens Pro is not working with a consultant who uses AI tools. They are working with a consultant who has built an operational layer — an AI organisation — that runs behind every engagement.

In practice, this means: context is never lost, because the infrastructure maintains it. Deliverables are produced at a pace and in parallel that a solo practitioner could not otherwise sustain. Quality is enforced by a system with no fatigue and no conflict of interest, not by a single person reviewing their own work. And my attention — strategic direction, design judgement, client relationship, problem framing — is applied where it cannot be delegated.

The system is documented and version-controlled at [github.com/faberludens-pro/ai-workflow-development](https://github.com/faberludens-pro/ai-workflow-development).
