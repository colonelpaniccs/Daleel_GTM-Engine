# Engineering Philosophy

## Ship before perfect

The first version went live against real signals before every edge case
was closed. A pipeline handling most of what it meets in production
teaches more in a week than one built to handle every imagined case in
advance.

## Measurement picks the method

An early resolution step leaned on model inference. Measured against
known answers, it was wrong often enough to matter, and was replaced
with something deterministic. Reasoning earns its place where judgment is
genuinely required, and a rule earns its place where the work is well
enough understood to write one.

## Provenance is not proof

Output is not credible because a capable model produced it or because a
step upstream usually works. Unaccountable outcomes are liabilities, and
what makes a result defensible is being able to account for how it got
there.

## Capabilities that outlast platforms

Every layer is defined by the job it does rather than the vendor
currently doing it. Platforms get repriced, acquired, and deprecated.
The job stays the same, and designing the system that way is what makes
replacing any piece possible.

## Every round, the same note

After 10+ years in B2B SaaS, I've watched every funding round become a
pitch. A new role becomes a congratulations note, and a pitch. This is an
active problem: every seller reading the same public sources produces the
same message, landing in an inbox that already holds forty of them. The
fix is to treat the event as a cue: a company entering a new market,
three seats opening in a function that never existed there before, a
tool stack that just changed shape. Real understanding starts with the
problem a persona faces inside their org. These details simply support
timely, relevant outreach.

> [!NOTE]
> These are stated as constraints in `design-principles.md` and as the
> mechanisms that enforce them in `governance.md`.
