# AI Components

Tools are named below.

> [!IMPORTANT]
> This repository does not include prompt content, scoring weights, model
> tuning parameters, or the reasoning chain behind a score.

| Capability                          | Current Implementation                                                                 | Why this layer exists |
|--------------------------------------|-------------------------------------------------------------------------------------------|-------------------------|
| Workflow orchestration                | Zapier: webhook triggers, conditional branching, sub-workflow composition | Coordinates every stage without owning any reasoning itself. If the orchestration platform changed tomorrow, the reasoning and scoring logic wouldn't have to. |
| Autonomous retrieval / browsing        | Zapier Agent, handles content requiring rendering or multi-step navigation to reach | Public information and accessible information are two different things. |
| Structured reasoning & extraction      | Claude (Anthropic API), model selection tiered by task complexity and call frequency                       | Rule-based scripts can't reliably turn an unstructured signal into a confident judgment. |
| Language / entity resolution support   | Vertex AI (Gemini), applied specifically to entity and domain resolution | Resolution and reasoning are different problems, requiring different models. |
| Monitoring & handoff                   | Leila, a named agent that evaluates pipeline health and flags what needs a person's judgment | An autonomous monitor provides regional and operational awareness, separating a genuinely quiet week from a silent failure. |
