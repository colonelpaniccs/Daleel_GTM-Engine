# Data Flow

> [!IMPORTANT]
> Capability-level flow only. No tier counts, no step numbers, no specific
> fetch/query mechanics.

```
Signal Sources
      │
      ▼
AI Reasoning & Enrichment
      │
      ▼
ICP Match & Scoring
      │
      ▼
CRM Write & Audit
      │
      ▼
Delivery & Action
```

Each arrow represents a validated contract between stages. See [`/examples`](../examples) for the input/output pair and the webhook contract.
