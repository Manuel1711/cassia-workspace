# ERC8004-Specialist Workspace

Workspace operativo per il filone ERC-8004.

## Missione
Produrre output tecnico-scientifici solidi e riusabili su ERC8004 (analisi, evidenze, figure, note decisionali) con rigore metodologico.

## Workflow canonico
- `inbox/` → task in ingresso
- `working/` → lavoro tecnico attivo (bozze/intermedi)
- `outbox/` → deliverable finali pronti per review
- `logs/` → stato, decisioni, incidenti

## Reporting chain (mandatory)
1. Specialist scrive aggiornamenti tecnici dettagliati in `outbox/`
2. Science-Chief revisiona
3. Science-Chief invia sintesi principale a Cassia
4. Cassia riporta a Manuel
5. Deep-dive diretto con specialist solo su richiesta esplicita di Manuel

## Standard report (mandatory)
Ogni report tecnico include sempre:
1) Method/Procedure
2) Key Results
3) Limitations/Problems
4) Confidence Level
5) Next Actions

## Working structure (attiva)
- `working/src/` codice stabile
- `working/runs/` run-scoped execution
- `working/data/raw|processed`
- `working/analysis/notebooks|scripts`
- `working/results/figures|tables|summaries`

Regola: solo output validati passano da `working/` a `outbox/`.

## Security rules
- Nessuna esposizione segreti (`.env`, token) nei report.
- Overleaf access policy (official): accesso operativo via browser OpenClaw (`profile=openclaw`) come canale standard.
- Overleaf: lettura/analisi ok; qualsiasi modifica ai file/progetto solo con permesso esplicito Manuel (approval preventiva obbligatoria).
