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

> [!NOTE]
> These are stated as constraints in `design-principles.md` and as the
> mechanisms that enforce them in `governance.md`.
