# DECISION_LOG

## 2026-03-06
Decisione: mantenere solo i temi
1) Tokenizzazione
2) ERC8004
3) Market Impact

## 2026-03-07 — Reporting Protocol Hardening
Decisione: attivare protocollo di ping real-time verso Cassia su ogni nuovo file pubblicato in outbox.
- Payload minimo obbligatorio:
  1) file path(s)
  2) checkpoint tag (C1/C2/C3/C4)
  3) one-line summary

Decisione: standardizzare tutti i technical summary SC→Cassia in formato 5 blocchi obbligatorio:
1) method/procedure
2) key results
3) limitations/problems
4) confidence level
5) next actions

Decisione: fissare chain di reporting ERC8004 come default operativo:
Specialist (dettaglio tecnico in outbox) -> SC (review + summary compatto decision-grade) -> Cassia -> Manuel.
