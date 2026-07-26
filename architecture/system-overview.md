# System Overview

The GTM Engine is always-on coverage across revenue signals, built to back
up a team's own instincts.

**What it does:**
- Identifies companies actively scaling their GTM motion
- Continuously monitors publicly available signals
- Scores signals against a defined ideal-customer profile, alongside
  what's already in your CRM
- Surfaces prioritized results to teams without manual research
- Updates the system of record

**Agentic behavior:**
- Intelligently interprets findings
- Infers the growth stage of a company's revenue function
- Automatically routes urgent alerts, plus a separate weekly digest in
  Slack and email, where teams already work

**Human judgment is reserved for:**
- Meaningful conversations with qualified accounts
- A rep requesting enrichment or an update on demand
- A case where the model's own confidence is genuinely in question, such
  as an erroneous spike in scoring

**Scope:**
- No live feed to babysit, just output on a cadence built for a rep's
  actual rhythm
- Every score lands directly in your CRM, enriching an existing account
  or creating a new one
- Signal sources are limited to compliant, publicly available data

> [!NOTE]
> The scoring framework and signal library behind these judgments stay
> private, and `docs/security.md` explains why. The output schema itself
> is public, see `/examples` to learn more.
