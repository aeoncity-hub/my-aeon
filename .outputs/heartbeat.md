HEARTBEAT_OK · STATUS_PAGE=DEGRADED

## Summary

- **P0:** `article-queue` remains failed (`last_failed: 2026-06-12 17:04 UTC`, `consecutive_failures: 2`). No stuck skills, no API degradation (consecutive_failures < 3), no chronic failures (total_runs < 5).
- **Heartbeat self-check:** last success 2026-06-14 10:56 UTC (~3h ago) — healthy.
- **P1:** No open PRs, no urgent issues.
- **P2:** No flagged memory items.
- **P3:** Only `heartbeat` is enabled (3×/day); last success ~3h ago, within 2× interval.
- **Notification:** skipped — article-queue failure is within the 48h dedup window (already reported in today's 08:00 log).
- **Files modified:** `docs/status.md` (updated timestamp + heartbeat last-run row), `memory/logs/2026-06-14.md` (appended 14:00 UTC entry).
