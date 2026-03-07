# ERC8004-Specialist MEMORY

## Persistent Directives

### 1) Reporting chain (mandatory)
- Specialist publishes detailed technical reports in `outbox/`.
- Science-Chief reviews and compresses to decision-grade summary.
- Cassia reports to Manuel.
- Direct deep-dive with specialist only when Manuel explicitly asks.

### 2) Scientific reporting standard (mandatory)
Every technical update must include:
1. Method / Procedure
2. Key Results
3. Limitations / Problems
4. Confidence Level
5. Next Actions

### 3) Real-time outbox ping (mandatory)
After each new outbox file, send immediate ping to Cassia with:
- file path(s)
- milestone/checkpoint tag
- one-line summary

### 4) Workspace workflow convention (approved by Manuel)
- `inbox/` receives tasks.
- `working/` contains draft/intermediate technical work.
- `outbox/` contains only final decision-ready deliverables.
- `logs/` stores status/decision trail.

Working structure standard:
- `working/src/` stable pipeline code
- `working/runs/` run-scoped execution folders
- `working/data/raw|processed`
- `working/analysis/notebooks|scripts`
- `working/results/figures|tables|summaries`

### 5) `src/` promotion policy (mandatory)
- You cannot move/promote code to `working/src/` autonomously.
- Promotion requires explicit approval from **Science-Chief**.

When proposing promotion, include:
1. path of candidate code
2. reusability justification
3. run evidence (log path + successful output)
4. I/O interface summary
5. risk/non-regression note

Only after SC approval may code be promoted and logged.

### 6) Security/operational boundaries
- Prefer workspace snapshots for execution; avoid direct operations on external source folders unless explicitly authorized.
- Never expose secrets (`.env` or tokens) in reports.
- Overleaf access standard: use OpenClaw dedicated browser (`profile=openclaw`) as default access channel.
- Overleaf edits require explicit Manuel approval (pre-approval mandatory before any change action).

### 7) SC-supervised P0 full-analysis execution (2026-03-07)
- Completed deliverables:
  - `outbox/ERC8004_FULL_ANALYSIS_REPORT_2026-03-07.md`
  - `outbox/ERC8004_FIGURE_BOOK_2026-03-07.md`
  - `outbox/ERC8004_INTERPRETIVE_NOTES_2026-03-07.md`
  - `outbox/figures/2026-03-07_full_analysis/` (PDF figure set)
- Checkpoints C1..C4 were pinged to Cassia as required.
