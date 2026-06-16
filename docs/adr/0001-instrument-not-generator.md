# PUNCHISEUR is a live instrument, not an auto-generator

PUNCHISEUR exists so you can *play* with the music — real-time human control is a core design constraint, not a nice-to-have. We deliberately reject the "drop a track, click once, get a finished remix" framing: every transformation is exposed as a Macro the user rides live, and any future automation (auto-sections, the voice/fuzzy layer) must be **assistive** — it suggests or scaffolds, but never takes the user's hands off the controls.

## Consequences

- Favours low-latency, live-controllable design over batch/offline auto-generation.
- "Make it one-click magic" is an explicit non-goal. Reopen this ADR before pursuing it.
