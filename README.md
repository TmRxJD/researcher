# Researcher

Researcher is a standalone, text-only agent skill for web research, fact-checking, and evidence reviews. It teaches agents how to frame a question, choose where to search, verify claims against original evidence, and explain what remains uncertain.

## Install in Codex

Clone the repository into your personal skills directory. This example uses the default Codex home.

```sh
git clone https://github.com/TmRxJD/researcher.git ~/.codex/skills/researcher
```

If you use a custom Codex home, clone into its `skills/researcher` directory instead. Open a new session and invoke `$researcher` with your research question. The skill uses the search and source tools available in your agent host. It has no runtime dependencies.

## Use it

> $researcher Verify what npm audit checks, using current npm documentation. Explain what a clean result can establish.

The [main workflow](SKILL.md) covers quick verification, deep investigations, and systematic reviews. Agents load the relevant guide when a task needs more depth.

- [Search techniques](references/search.md) covers focused queries, source discovery, citation chaining, and formal database strategies.
- [Source verification and synthesis](references/evidence.md) covers provenance, conflicting evidence, quantitative claims, and uncertainty.
- [Evidence review and reproducibility](references/evidence-review.md) covers eligibility criteria, search logs, screening, and synthesis.
