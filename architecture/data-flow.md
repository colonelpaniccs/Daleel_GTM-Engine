# Data Flow

> [!IMPORTANT]
> Capability-level flow only. No tier counts, no step numbers, no specific
> fetch/query mechanics.

```
Signal Sources
      │
      ▼
Event Orchestration
      │
      ▼
Reasoning & Enrichment
      │
      ▼
Schema Validation
      │
      ▼
System of Record
      │
      ▼
Notification & Audit
```

Each arrow represents a validated contract between stages. See `/examples`
for the input/output pair and the webhook contract.
