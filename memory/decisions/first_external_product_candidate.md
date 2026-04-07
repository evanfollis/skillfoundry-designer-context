# Decision: First External Product Candidate

## Decision

The first external product candidate is `launchpad-lint`, a narrow MCP utility that
helps technical builders turn a server that already works into a launch-ready package
for marketplaces such as AgenticMarket.

## Date

2026-04-06

## Why

- It is more legible than the docs-to-tool-surface idea.
- It has lower implementation variance than broad API-doc synthesis.
- It fits the chosen ICP directly.
- It aligns with the first external distribution surface we already chose.
- It should be possible to validate install-to-first-value in one session.

## Product Boundary

`launchpad-lint` is an external product candidate.

It is distinct from:

- `bottleneck-radar`, which is an internal mechanism for opportunity discovery
- the broader Skillfoundry platform, which remains substrate and coordination

## Revisit Trigger

Revisit this decision if:

- early design reveals that the surface cannot stay narrow,
- the utility reads as generic copy generation rather than decision support,
- or a higher-ranked candidate becomes materially easier to validate.
