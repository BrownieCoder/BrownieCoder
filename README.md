<p align="center">
  <img src="assets/cats-banner-v6.png" alt="Four cats sharing a sunny developer workspace with code, system diagrams, and glasses: a lynx-point Ragdoll, a blue-golden shaded cat, a black Devon Rex, and a calico Devon Rex." width="100%">
</p>

<p align="center">
  <strong>Solutions Architect · AI &amp; Full-Stack Engineering</strong><br>
  <a href="mailto:waynecode96@gmail.com">Get in touch</a> ·
  <a href="https://github.com/BrownieCoder?tab=repositories&amp;type=source">Explore my projects</a>
</p>

I’m Wayne. I design and build AI applications, integrations, and full-stack tools that turn complex workflows into useful software.

My projects span research automation, evaluation dashboards, browser tools, and full-stack applications, connecting **messy inputs, AI models, and useful workflows**.

I care about the parts that make these systems dependable: validated outputs, reviewable context, explicit state, and recovery when a step fails.

## Recent Open Source Contributions

### [Docling](https://github.com/docling-project/docling) · 70k+ stars

Contributed to a document-processing toolkit for generative AI, with integrations across LangChain, LlamaIndex, and the broader AI ecosystem.

**[Merged PR #5228 — Prevent silent content loss in HTML email ingestion](https://github.com/docling-project/docling/pull/5228)**

Fixed silent loss of HTML email footers by preserving content-layer semantics end to end, from the HTML backend through the email document model and JSON export. Footer content is also available through opt-in Markdown export, while default body-only output and plain-text precedence remain unchanged.

Added end-to-end regression coverage for HTML-only and multipart messages, blank plain-text alternatives, footer-only content, escaping, and consistency across the document model and export formats.

### [Karakeep](https://github.com/karakeep-app/karakeep) · 30k+ stars

Contributed to an open-source bookmarking app with AI-powered tagging and full-text search.

**[Merged PR #3053 — Search by notes and highlights](https://github.com/karakeep-app/karakeep/pull/3053)**

Implemented `has:notes` and `has:highlights` filters across database queries, smart lists, and search autocomplete, with documentation and regression tests.

**[Merged PR #3299 — Consistent manual summary status](https://github.com/karakeep-app/karakeep/pull/3299)**

Updated successful manual summaries and their status in the same database write, with regression tests for recovery, inference errors, empty responses, and cross-user access.

### [SayAll](https://github.com/HD838A/remote-mic-app) · 2.6k+ stars

Contributed to a native macOS app that turns Bluetooth voice remotes into wireless microphones and customizable controls.

**Merged PRs: [#829](https://github.com/HD838A/remote-mic-app/pull/829) · [#844](https://github.com/HD838A/remote-mic-app/pull/844) · [#888](https://github.com/HD838A/remote-mic-app/pull/888) · [#913](https://github.com/HD838A/remote-mic-app/pull/913)**

Fixed left/right modifier-key handling, unified native menu-bar interactions, added per-device remote battery status, and made focus-option cards fully clickable. Included regression tests and manual macOS validation.

## Selected work

| Project | What to look for | Stack |
| :--- | :--- | :--- |
| **[Agent Lens](https://github.com/BrownieCoder/agent-lens)** | Compare report quality across prompt versions. Inspect human review, judge calibration, and cost/latency tradeoffs. | Python · FastAPI · React |
| **[Signal Workbench](https://github.com/BrownieCoder/signal-workbench)** | Run an offline research pipeline with synthetic crypto evidence, proposal validation, budget fallback, and resumable local delivery. | Python · SQLite |
| **[Reply Copilot](https://github.com/BrownieCoder/reply-copilot)** | AI writing assistance inside the browser, with reviewable context, explicit site access, and protection against overwriting newer drafts. | JavaScript · Chrome MV3 |
| **[CloseLoop](https://github.com/BrownieCoder/closeloop)** | A decision-management PWA with explicit state transitions, preserved reasoning, and separate data/asset caching. | TypeScript · React · D1 |

Also building **[Agent Title Renamer](https://github.com/BrownieCoder/agent-title-renamer-skill)**: a portable skill for keeping AI conversation titles useful and consistent.

Away from the keyboard, I share my home with four cats. They also supervise the keyboard. (´•༝•)`

## How I work

- **Make behavior inspectable.** Small modules, documented decisions, and examples you can run locally.
- **Test the failure paths.** Invalid model output, stale editor state, interrupted delivery, and data boundaries deserve explicit handling.
- **Connect architecture to delivery.** System boundaries, integration choices, APIs, and data pipelines through to the interface people use.

**Tools I reach for:** Python, FastAPI, SQLAlchemy, SQLite, TypeScript, React, Chrome extensions, Cloudflare Workers, D1, and GitHub Actions.

## Let's build something useful

Open to **remote opportunities** in solutions architecture, AI applications, research tooling, data automation, and full-stack development. Comfortable with asynchronous collaboration in English and Mandarin.

**[waynecode96@gmail.com](mailto:waynecode96@gmail.com)**
