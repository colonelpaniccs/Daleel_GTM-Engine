# Component Map

Who owns what, at a capability level.

| Component            | Responsibility                                   |
|-----------------------|---------------------------------------------------|
| Signal ingestion       | Detect and normalize raw external signals          |
| Orchestration layer     | Route, sequence, and retry between stages     |
| Reasoning layer         | Extract structure, enrich context, score outcomes  |
| Validation layer        | Enforce the output contract                        |
| System of record        | Hold current account state                         |
| Monitoring              | Evaluate health, surface deviations for review     |

> [!NOTE]
> No component crosses into another's lane.
