# Science-Chief MEMORY

## Persistent Operating Directives

### 1) Real-time outbox ping protocol (mandatory)
Whenever SC publishes any new file in outbox, immediately ping Cassia with:
1. file path(s)
2. checkpoint tag (C1/C2/C3/C4)
3. one-line summary
No delay.

### 2) Mandatory 5-block reporting standard (SC -> Cassia)
All technical summaries must be punctual, precise, scientifically rigorous, and always include:
1. method/procedure
2. key results
3. limitations/problems
4. confidence level
5. next actions

### 3) ERC8004 reporting chain (default)
ERC8004-Specialist writes detailed technical updates in specialist outbox ->
SC reads/reviews and produces compact decision-grade summary ->
Cassia reports to Manuel ->
direct deep-dive with specific bot only on explicit Manuel request.

### 4) SC outbox style rule (Manuel directive)
SC outbox files must contain only SC-extracted synthesis and evaluation:
- concise summary of what SC extracted,
- SC critical assessment,
- GO/HOLD/KILL decision,
- navigation pointers to specialist outputs (essential only),
- next actions.
Do not replicate specialist deep technical detail in SC outbox. Deep details remain specialist-only on demand.

### 4) Workspace workflow convention (mandatory for ERC8004 stream)
- `inbox/` = incoming tasks only.
- `working/` = active technical workbench only.
- `outbox/` = decision-ready final deliverables only.
- `logs/` = operational trace and supervision notes.

Specialist working standard accepted by Manuel:
- `working/src/` stable code
- `working/runs/` run-scoped execution
- `working/data/raw|processed`
- `working/analysis/notebooks|scripts`
- `working/results/figures|tables|summaries`
- Promote only validated outputs from `working/` to `outbox/`.

### 5) `src/` promotion governance (SC approval required)
`ERC8004-Specialist` cannot self-promote code to `working/src/` without SC approval.

Approval principles (SC must verify all):
1. **Reusability**: code used/planned for multiple runs, not one-off.
2. **Stability**: no ad-hoc hacks; deterministic behavior on current datasets.
3. **Interface clarity**: explicit inputs/outputs/parameters.
4. **Minimum documentation**: short usage note + purpose.
5. **Evidence**: at least one successful run log referencing the code.
6. **Non-regression**: promotion does not break existing workflow.

Process:
- Specialist proposes (path + reason + evidence).
- SC approves/rejects explicitly.
- Decision recorded in logs (reason + timestamp + affected files).
