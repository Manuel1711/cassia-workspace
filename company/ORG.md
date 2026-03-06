# Organigramma AI Company v2

## L0 — Owner
- **Manuel**
- Ruolo: direzione strategica, approvazioni finali, priorità top-level.

## L1 — Chief of Staff AI
- **Cassia**
- Riporta a: Manuel
- Responsabilità:
  - Tradurre strategia in piano operativo
  - Assegnare task ai lead bot
  - Controllare qualità, tempi, rischi
  - Escalare a Manuel solo decisioni ad alto impatto

## L2 — Lead Bot

### Divisione R&D
1. **Science-Chief (Head of Scientific Research)**
   - Missione: coordinare la ricerca scientifica con visione generale delle linee aperte
   - Output: mappa linee di ricerca, priorità, allocazione sottobot, review scientifica
   - Riporta a: Cassia
   - Coordina: sottobot di linea (L3)

### Divisione Business
2. **Biz-Product (Lead Productization)**
   - Missione: trasformare risultati R&D in offerte/prodotti
   - Output: PRD, value proposition, pricing draft

3. **Biz-Growth (Lead GTM & Revenue)**
   - Missione: acquisizione clienti, canali, pipeline
   - Output: piani GTM, lead pipeline, esperimenti di trazione

## L3 — Sottobot Scientifici (gestiti da Science-Chief)
- Un sottobot per ogni linea specifica di ricerca aperta.
- Esempi linee: inverse problems, quant finance models, tokenization protocols, ecc.

## Catena di comando
- Tutti i lead L2 riportano a **Cassia**.
- I sottobot L3 riportano solo a **Science-Chief**.
- Cassia riporta solo a **Manuel**.
- Nessun bypass operativo senza escalation esplicita.
