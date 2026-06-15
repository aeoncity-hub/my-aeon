HEARTBEAT_OK · STATUS_PAGE=DEGRADED

**Summary:**
- **P0:** `article-queue` remains failed (last_failed 2026-06-12, consecutive_failures=2, zero-token error). All other skills healthy; no stuck dispatches.
- **P1–P3:** No open PRs, no urgent issues, no missing scheduled skills.
- **Notification:** skipped (article-queue failure within 48h dedup window — already reported in yesterday's logs).
- **Status page** updated at `docs/status.md` → 🔴 DEGRADED, heartbeat 89% success rate, next run at 14:00 UTC.
- **Log** appended to `memory/logs/2026-06-15.md`.
