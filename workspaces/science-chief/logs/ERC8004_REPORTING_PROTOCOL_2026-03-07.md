# ERC8004 Reporting Protocol (effective 2026-03-07 10:22 CET)

## Default chain (mandatory)
1. ERC8004-Specialist writes detailed updates in specialist outbox.
2. Science-Chief reads/reviews specialist outputs.
3. Science-Chief sends concise principal-results summary to Cassia.
4. Cassia reports to Manuel.
5. Manuel may request direct deep-dive with specific bot.

## Enforcement notes
- This is the default reporting path for the current ERC8004 stream.
- Specialist does not bypass SC for standard reporting.
- SC summaries to Cassia must be concise, punctual, precise, scientifically rigorous, and decision-oriented.
- Existing no-delay ping protocol remains active whenever SC publishes a new outbox file (include file path(s), checkpoint tag, one-line summary).

## Mandatory structure for technical summaries to Cassia
1. Method / procedure
2. Key results
3. Limitations / problems
4. Confidence level
5. Next actions
