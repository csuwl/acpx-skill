# acpx-team Known Bugs

No open bugs at this time.

---

## Historical Bug Records

### Butler Bugs (2026-03-29) — All Fixed

12 bugs found during code review and scenario testing, all resolved:
bare glob patterns (BUG-1~5), `[[ ]] &&` return pattern (BUG-6),
Chinese slug fallback (BUG-7), workflow auto-advance logic (BUG-8),
batch regex precision (BUG-9), octal ID interpretation (BUG-10),
stdout pollution in board_next (BUG-11), dry-run missing unblock (BUG-12).

### Council Bugs (2026-03-28) — All Fixed Except External

| # | Bug | Status | Fix |
|---|-----|--------|-----|
| 1 | Synthesize error message unhelpful | **FIXED** | Improved error propagation |
| 2 | Execute hangs without plan | **FIXED** | Added early validation |
| 3 | Custom role template duplicate text | **FIXED** | Fixed template construction |
| 4 | acpx ACP agent connection failure | **EXTERNAL** | Requires genuine Anthropic API |
| 5 | `--single-agent` auto-set `--orchestrator` | **FIXED** | Added auto-set logic |
| 6 | Adversarial session name collision | **OPEN** | Run adversarial protocols sequentially |
