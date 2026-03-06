# Bot Workspaces

Questa cartella contiene i workspace operativi separati per i lead bot.

## Struttura standard per ogni bot
- `inbox/` -> task ricevuti da Cassia
- `working/` -> lavoro in corso
- `outbox/` -> deliverable finali pronti per review
- `logs/` -> log operativi del bot

## Workspace lead attivi
- `science-chief/`
- `biz-product/`
- `biz-growth/`

## Archivio
- `archive/` contiene workspace non più attivi (es. vecchia separazione rd-scientist / rd-builder)

## Regola operativa
Ogni bot lavora nel proprio workspace e pubblica output in `outbox/`.
Cassia raccoglie e consolida nel workspace centrale (`company/control`).
