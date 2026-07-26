# Component Map

Who owns what, at a capability level.

## Stages

| # | Stage                     | Responsibility                                          |
|---|---------------------------|---------------------------------------------------------|
| 1 | Signal Sources            | Detect and normalize raw external signals               |
| 2 | Enrichment & AI Reasoning | Resolve entities, gather context, extract structure     |
| 3 | ICP Match & Scoring       | Judge fit against the profile, assign a priority tier   |
| 4 | CRM Enrichment            | Enforce the output contract, hold current account state |
| 5 | Delivery & Action         | Route what matters to the people who act on it          |

## Pipeline-wide

| Component     | Responsibility                                 |
|---------------|------------------------------------------------|
| Orchestration | Route, sequence, and retry between stages      |
| Monitoring    | Evaluate health, surface deviations for review |
