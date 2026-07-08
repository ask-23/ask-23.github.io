# ask-23.github.io

Source for my AI engineering portfolio. If you landed here from GitHub, the rendered page is the thing to read:

**→ [ask-23.github.io](https://ask-23.github.io)**

The site is mostly routing — a curated set of public artifacts from my AI delivery work, with links to the repos and a few essays. Not a complete inventory.

## What it points to

- **[composable-me](https://github.com/ask-23/composable-me)** — a truth-constrained, multi-agent system that generates job applications from real source material and refuses to invent anything it can't trace to a source. CLI, per-run audit report, real test suite.
- **[ai-delivery-guards](https://github.com/ask-23/ai-delivery-guards)** — a small Go CLI that scans for LLM call sites and fails CI when the surrounding evidence isn't there: eval coverage, rollback metadata, observability markers.
- **[agentic-patterns](https://github.com/ask-23/agentic-patterns)** — bounded agentic workflow examples, defined by where the workflow stops, escalates, or refuses.
- **[architecture-notes](https://github.com/ask-23/architecture-notes)** — short essays on the operational middle of AI systems.

## Build

Static HTML, no build step. `index.html` is served directly by GitHub Pages; `.nojekyll` disables Jekyll processing. Edit `index.html` and push to `main` to deploy.
