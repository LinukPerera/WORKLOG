# Work Log / Time Sheet

Chronological record of work done across all active projects for Intertranslations and Alpha, organized by
date. Each day's file consolidates the detailed logs kept inside the
individual project repos, so this repo acts as the single source of truth
for timesheet purposes.

Source project repos:
- `paliverse_mistranslations_finder_webapp` (aicorrector.paliverse.org go-live)
- `Alpha-Log-Probs` (logprobs-based MT quality estimation feasibility study)
- `Tikka_translation_process` (Tikka n-gram mapper table + four-AI translation experiment)

## Summary

| Date | Hours logged | Projects | Notes |
|---|---|---|---|
| [2026-10-07](2026-10-07.md) | 10h total — PaliVerse 6h (12:30–18:30), Tikka 1.5h, LogPrompts Research design/planning 2.5h | PaliVerse go-live, Tikka n-gram mapper + S0101 experiment, LogPrompts Research (design) | |
| [2026-10-08](2026-10-08.md) | 9h total, contiguous 11:30–20:30 — PaliVerse 4h (11:30–15:30) + 2h (18:30–20:30), LogPrompts Research build-out 3h (15:30–18:30) | PaliVerse go-live (auth bug investigation, then OAuth redirect flow + a staged/production writeback bug), LogPrompts Research (Alpha-Log-Probs scaffolding/build) | |
| [2026-10-09](2026-10-09.md) | 10h total, contiguous 11:30–21:30 — LogPrompts Research 3h (11:30–14:30) + 5h (16:30–21:30), PaliVerse 2h (14:30–16:30) | LogPrompts Research (data-governance cleanup, terminology-impact arm, vLLM backend built), PaliVerse go-live (API key rotation, UI relabeling) | |
| [2026-10-12](2026-10-12.md) | 8.5h total (11:30–20:00) — LogPrompts Research | LogPrompts Research (ran both study arms on real data, no-go result, wrote FEASIBILITY_REPORT.md, built the audit/presentation package) | |
| [2026-10-13](2026-10-13.md) | 7h total — LogPrompts Research 4h (11:30–15:30), Tikka 3h (16:30–19:30) | LogPrompts Research (OpenAI API compatibility research, experiments plan, live key testing), Tikka (S0101 experiment logging/example-matcher/output-format fixes, live 4-provider run build and retry) | |
| [2026-10-14](2026-10-14.md) | 7h total — LogPrompts Research 1.5h (11:30–13:00), PaliVerse 1h (14:00–15:00, meeting), Tikka 4.5h (15:00–19:30) | LogPrompts Research (OpenAI judge pilot, severity-stratified AUC finding reverses model recommendation), PaliVerse (meeting), Tikka (S0101 live-run results, 6-metric quality comparison, cost accounting) | |
| [2026-10-15](2026-10-15.md) | 7h total — LogPrompts Research 3h (11:30–14:30) + 2h (17:30–19:30), Tikka 2h (15:30–17:30) | LogPrompts Research (judge round 2, all 8 signal layers closed, OpenAI feasibility report, Experiments 2/3 run, Part 2 presentation guide), Tikka (mapper-table branch pushed, S0101 phase closed, Info Tabs evaluation started, production-DB network blocker) | |
| [2026-10-16](2026-10-16.md) | 8h total — LogPrompts Research 3h (11:30–14:30) + 1.5h (15:30–17:00, meeting), Tikka 3.5h (17:00–20:30) | LogPrompts Research (presentation updates, terminology/results support ahead of a meeting, meeting with Alpha), Tikka (S0101: added DeepSeek + true Meta standard-tier run, caught a Meta pricing-tier mislabel) | |
| [2026-10-19](2026-10-19.md) | 10h total, contiguous 10:30–20:30 — Tikka 3.5h (10:30–14:00) + 3.5h (17:00–20:30), LogPrompts Research 3h (14:00–17:00) | Tikka (S0101 six-provider results/correction, Google Gemini/Gemma investigated and blocked by quota, Info Tabs status check), LogPrompts Research (error-category evaluation phase, moving to new hardware) | No entries found for 2026-10-17/18 (weekend) |
| [2026-10-20](2026-10-20.md) | 12h total, contiguous 10:30–22:30 — LogPrompts Research 2h (10:30–12:30) + 2h (20:00–22:00), Tikka 7.5h (12:30–20:00) + 0.5h (22:00–22:30) | LogPrompts Research (handoff to a new Windows PC, local DeepSeek judge matches the hosted judges, error-category/sub-category results), Tikka (S0101 Gemini run completed; Info Tabs pipeline rebuilt from scratch and run live across 4 providers, ~$80.86 real cost, one unresolved Gemini billing discrepancy) | LogPrompts Research now pulled from its GitHub repo, not read locally — work moved off this VM |

**Total hours logged so far: 88.5h** (10h on 2026-10-07, 9h on
2026-10-08, 10h on 2026-10-09, 8.5h on 2026-10-12, 7h on 2026-10-13, 7h
on 2026-10-14, 7h on 2026-10-15, 8h on 2026-10-16, 10h on 2026-10-19,
12h on 2026-10-20).
