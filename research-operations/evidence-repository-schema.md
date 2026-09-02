# Evidence Repository Schema

- **Status:** Empty schema; no participant data included

## Study Record

| Field | Purpose |
| --- | --- |
| Study ID and title | Stable reference |
| Product decision | Why the research exists |
| Owner and partners | Accountability |
| Dates and status | Currency |
| Method and sample | Interpretation boundary |
| Consent version | Permission audit |
| Evidence location | Restricted source, never raw data in public Git |
| Readout and decision log | Research influence |

## Evidence Record

| Field | Example Format |
| --- | --- |
| Evidence ID | `FI-E-001` |
| Participant ID | `FI-P01` |
| Research question | `FI-RQ2` |
| Source and task | `Interview / comparison task` |
| Observation or consented excerpt | `[De-identified evidence]` |
| Researcher interpretation | `[Separate field]` |
| Code | `trust-signal` |
| Access restriction | `Research team only` |
| Public sharing permission | `No / approved excerpt only` |

## Finding Record

Connect each finding to evidence IDs, counterevidence, sample coverage, interpretation, confidence, limitation, recommendation, decision owner, stakeholder disposition, and follow-up signal.

## Taxonomy Rules

- An observation describes what occurred.
- An excerpt preserves participant language within consent limits.
- An interpretation explains what evidence may mean.
- A finding combines evidence into a decision-relevant pattern.
- An insight reframes understanding and must still be traceable.
- A recommendation proposes action; it is not evidence.
- A decision records what the organization will do and why.
