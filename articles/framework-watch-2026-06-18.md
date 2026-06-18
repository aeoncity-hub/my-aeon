# AI Framework Watch — 2026-06-18

**Verdict:** RELEASE WEEK: 3 frameworks shipped — langgraph, crewAI, mastra

**Tracked:** 9 of 9 frameworks  ·  **Unreachable:** 0  ·  **Anchor:** aaronjmars/aeon

> **COLD START** — first run; no prior state. All 7d/30d deltas baseline this run and will be meaningful from run 2 onward.

---

## Ranked table

*(COLD START: sorted by current star count. Anchor pinned top. Deltas available next run.)*

| Framework | Stars | 7d Δ | 30d Δ | Releases (7d) | Breaking? | Headline |
|-----------|------:|------|-------|:-------------:|:---------:|---------|
| aaronjmars/aeon | 520 | — | — | 0 | — | — |
| microsoft/autogen | 59,053 | — | — | 0 | — | ⚠ last push 2026-04-15; last release Sep 2025 |
| crewAIInc/crewAI | 53,872 | — | — | 2 | — | 1.14.7 stable + 1.14.8a [PRE] |
| run-llama/llama_index | 50,204 | — | — | 0 | — | — |
| stanfordnlp/dspy | 35,112 | — | — | 0 | — | — |
| langchain-ai/langgraph | 35,107 | — | — | 2 | — | langgraph==1.2.5 + cli==0.4.30 |
| huggingface/smolagents | 27,918 | — | — | 0 | — | — |
| mastra-ai/mastra | 25,190 | — | — | 1 | — | @mastra/core@1.42.0 |
| pydantic/pydantic-ai | 17,826 | — | — | 0 | — | v2.0.0b7 shipped Jun 10 (just outside window) |

---

## Releases (7-day window: 2026-06-11 → 2026-06-18)

### langchain-ai/langgraph
- **langgraph==1.2.5** (2026-06-12) — Patch release; changes since 1.2.4. No breaking markers.
- **langgraph-cli==0.4.30** (2026-06-16) — CLI tooling update; changes since cli==0.4.29.

### crewAIInc/crewAI
- **1.14.7** (2026-06-11) — Stable release; what's changed not detailed in first line.
- **1.14.8a** (2026-06-18) [PRE] — Alpha drop; what's changed not detailed in first line.

### mastra-ai/mastra
- **@mastra/core@1.42.0** (2026-06-12) — "June 12, 2026" highlights release; stable minor bump.

---

## Momentum picks

*(COLD START — no prior state to compute 7d star deltas. Picks available from run 2 onward.)*

---

## Anchor position

aeon (520 stars) sits at the base of the cohort by raw star count — expected for a newer, opinionated GitHub-native runtime competing against frameworks with 2–4 years of community accumulation. It pushed code on 2026-06-17, confirming active development. The repo has no published GitHub Releases, so the "Releases (7d)" column will read 0 every run — that's a data gap to keep in mind; aeon ships via branch commits rather than tagged releases. The first meaningful comparison point for aeon will be week 2, once 7d star deltas are available.

---

## Notable signals

### autogen dormancy
microsoft/autogen has 59,053 stars (largest in the cohort) but shows `pushed_at: 2026-04-15` — 64 days of silence on the main branch — and its last published release was `python-v0.7.5` in September 2025, now 9 months ago. The repo is not archived. This pattern (stars static, no commits, no releases) typically means either a major rewrite in a separate branch/repo, or the project has entered maintenance-only mode. Operators depending on autogen should verify whether active development has migrated elsewhere before adopting new features.

### pydantic-ai dual release track
pydantic-ai is running parallel tracks: stable `v1.107.0` (released 2026-06-10) alongside a `v2.0.0b7` beta (also 2026-06-10) — both just outside this week's window. The v2 beta line has been steady since at least v2.0.0b5 (2026-06-02), suggesting a v2 stable is imminent. A major version bump from a type-safety-focused framework typically carries breaking changes; worth tracking closely over the next 2–3 weeks.

---

## Source status

`gh_api: ok · reachable: 9/9 · releases_lookup: 9/9 · breaking_signals_fired: 0`
