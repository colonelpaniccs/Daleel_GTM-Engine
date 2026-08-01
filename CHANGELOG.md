# Changelog

All notable changes to this public repository are recorded here, loosely
following [Keep a Changelog](https://keepachangelog.com/).

## [0.2.0] - 2026-08-01

### Added
- `images/slack-demo.gif` and `images/weekly-digest-demo.gif`: short
  recordings of a company submitted in chat returning a scored result,
  and of the scheduled digest as it arrives
- `README.md`: "Walkthroughs" section holding both recordings

### Changed
- `/examples` path references in `README.md`,
  `architecture/system-overview.md`, and `architecture/data-flow.md` are
  now links
- `images/README.md`: descriptions added for both new recordings;
  `build-activity.png`'s entry updated to reflect it no longer appears
  in `README.md`

### Removed
- `images/build-activity.png` no longer embedded in `README.md`. The
  file itself is unchanged and remains in `/images`

## [0.1.1] - 2026-07-26

### Changed
- `images/pipeline-flow.png`: refreshed to a five-stage pipeline view.
  Signal Sources, Enrichment & AI Reasoning, ICP Match & Scoring,
  CRM Enrichment, Delivery & Action
- `images/example-workflow.png`: refreshed to match, with the enrichment
  and scoring stage shown between input and result
- Both diagrams moved onto a shared visual system
- `README.md`: "Architecture Overview" section and image alt text updated
  to the five-stage view
- `images/README.md`: descriptions updated to match
- `architecture/data-flow.md`: updated to the five-stage view, with
  orchestration and monitoring described as cross-cutting concerns
- `architecture/component-map.md`: updated to match, stages and
  cross-cutting concerns listed separately

## [0.1.0] - 2026-07-26

### Added
- `docs/philosophy.md`, `docs/design-principles.md`, `docs/governance.md`,
  `docs/ai-components.md`, `docs/roadmap.md`
- `architecture/system-overview.md`, `architecture/data-flow.md`,
  `architecture/component-map.md`
- `/examples`: fictional input/output pair and the webhook payload contract
- `CONTRIBUTING.md`

### Changed
- `README.md`: links to the full documentation set, scope statement tightened
- `docs/security.md`: least-privilege and credential-handling wording

## [Unreleased]
- Initial scaffold: repository structure, documentation, and fictional examples.
