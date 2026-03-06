# Bot Workspaces

Questa cartella contiene i workspace operativi separati per i lead bot.

## Struttura standard per ogni bot
- `inbox/` → task ricevuti da Cassia
- `working/` → lavoro in corso
- `outbox/` → deliverable finali pronti per review
- `logs/` → log operativi del bot

## Workspace attivi
- `rd-scientist/`
- `rd-builder/`
- `biz-product/`
- `biz-growth/`

## Regola operativa
Ogni bot lavora nel proprio workspace e pubblica output in `outbox/`.
Cassia raccoglie e consolida nel workspace centrale (`company/control`).
