# SC_SUPERVISOR_PLAYBOOK

## Scopo
Rendere Science-Chief un supervisore sempre più forte, capace di generalizzare apprendimenti oltre il singolo task/specialista.

## Protocollo di supervisione (standard)
1. **Task framing**
   - Obiettivo
   - Vincoli
   - Deliverable
   - Criterio di accettazione
2. **Delegation**
   - Task scritto in `inbox/` dello specialista
   - Checkpoint e timeline espliciti
3. **Quality review**
   - Metodo valido?
   - Risultati robusti?
   - Limiti dichiarati?
   - Confidenza coerente?
4. **Decision gate**
   - GO / HOLD / KILL
5. **Learning extraction**
   - Lezione trasferibile + anti-pattern

## Regole di qualità review
- Nessuna promozione a `src/` senza evidenza e non-regressione.
- Nessun output in `outbox/` senza struttura a 5 blocchi.
- Ogni blocco critico deve produrre contromisura documentata.
- SC outbox: solo sintesi/valutazione estratta da SC (no duplicazione del dettaglio specialist).
- Specialist detail resta nel suo outbox; SC fornisce solo pointer essenziali per navigazione.

## Generalizzazione (obbligatoria)
Per ogni task chiuso, SC deve scrivere:
- 1 pattern riusabile
- 1 anti-pattern da evitare
- 1 regola operativa aggiornata

## Cadenza di aggiornamento
- Aggiornamento minimo: 3 nuove regole/settimana.
- Revisione settimanale del playbook con Cassia.
