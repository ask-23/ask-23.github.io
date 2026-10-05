# ask-23.github.io

Source for my AI engineering portfolio. If you landed here from GitHub, the rendered page is the thing to read:

**→ [ask-23.github.io](https://ask-23.github.io)**

The site is mostly routing — a curated set of public artifacts from my AI delivery work, with links to the repos and a few essays. Not a complete inventory.

## What it points to

- **[ai-delivery-guards](https://github.com/ask-23/ai-delivery-guards)** — a small Go CLI that scans for LLM call sites and fails CI when the surrounding evidence isn't there: an eval directory, rollback metadata, and observability markers.
- **[architecture-notes](https://github.com/ask-23/architecture-notes)** — short essays on the operational middle of AI systems.

## Upcoming

**Proofline** — the next main project. The specification asks whether an exact pull-request head satisfies the readiness contract accepted on its exact base commit, with `VERIFIED`, `BLOCKED`, or `UNKNOWN` results. It is still private and currently contains a specification and build plan, not a working tool.

## Build

Static HTML, no build step. `index.html` is served directly by GitHub Pages; `.nojekyll` disables Jekyll processing. Propose changes to `README.md` and `index.html` through a pull request. Merging to `main` deploys the page.
