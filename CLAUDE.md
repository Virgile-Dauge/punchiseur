# PUNCHISEUR

Take a song you like and **punch it up** — apply style presets (acid, hardcore, psytrance, …) on top of an existing track, built around Strudel-style live-coding music patterns.

> Project still being shaped. Domain language and decisions land in `CONTEXT.md` + `docs/adr/` via `/grill-with-docs`.

## Agent skills

### Issue tracker

Issues and PRDs live as GitHub issues (the `gh` CLI). The GitHub repo is **not created yet** — run `git init` + `gh repo create` before first use, otherwise `gh` can't infer the repo from a remote. See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage labels, default names (`needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: one `CONTEXT.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.
