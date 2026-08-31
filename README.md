# David Vornholt

**I build product software, LLM systems, and the engineering infrastructure that keeps them reliable.**

My work spans product design, typed application architecture, AI systems, and
declarative infrastructure. I care about explicit contracts, fail-closed
quality gates, and systems that remain understandable as they grow.

## How I build

### [standards](https://github.com/davidvornholt/standards)

The public engineering contract behind the repositories I maintain: a shared
operating model for humans and agents, reusable skills, fail-closed quality
gates, and a sync engine that keeps projects aligned.

- **Fail closed.** Linting, types, tests, accessibility, structure, and selected
  repository settings are checked mechanically.
- **Verify the review.** Agent review loops fix findings and then verify the
  resulting changes.
- **Share one contract.** Repositories inherit the same standards instead of
  drifting independently.
- **Strengthen over time.** Gates improve upstream and are never weakened just
  to make a change pass.

## Current work

- **[Atrium](https://david.vornholt.online/works/atrium)** — Founder. A platform
  for a school's day-to-day operations, built around one typed contract from
  API to screen and currently being piloted at its first school.
- **[ProsaBridge](https://david.vornholt.online/works/prosabridge)** — Co-founder
  & CTO. Context-aware LLM translation for complete manuscripts while
  preserving terminology, document structure, and editorial workflows.
- **[Freie Evangelische Schule Kirchheim](https://david.vornholt.online/works/fes-kirchheim)**
  — Volunteer lead full-stack developer. A website engagement that grew into
  declarative infrastructure and the first Atrium pilot.

## Selected open-source projects

- **[runlet](https://github.com/davidvornholt/runlet)** — Secure, ephemeral
  GitHub Actions runner orchestration for NixOS hosts and rootless Podman.
- **[mail-mcp](https://github.com/davidvornholt/mail-mcp)** — A draft-only IMAP
  MCP server and CLI on one shared Effect core; it reads and drafts, but never
  sends.
- **[punktlandung](https://github.com/davidvornholt/punktlandung)** — Grade
  tracking for the Gymnasium in Baden-Württemberg, including weighted averages,
  report previews, and study days.
- **[portfolio](https://github.com/davidvornholt/portfolio)** — The source
  behind my portfolio: typed content, case studies, a shared design system, and
  declarative delivery.

## Engineering focus

- **Product engineering:** TypeScript, Effect, Bun, Next.js, TanStack Start,
  PostgreSQL, and Tailwind CSS.
- **AI engineering:** LLM pipelines, MCP servers, structured outputs, agent
  skills, and verified review loops.
- **Infrastructure:** NixOS, OpenTofu, Podman, SOPS, GitHub Actions, and Caddy.
- **Quality:** strict TypeScript, Biome, Playwright + Axe, WCAG 2.2 AA, and
  fail-closed CI.

## Elsewhere

[Portfolio](https://david.vornholt.online) ·
[LinkedIn](https://www.linkedin.com/in/david-vornholt-055239366) ·
[Email](mailto:david@vornholt.online)
