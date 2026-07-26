# Designer Context

This repository is the canonical context lineage for one Skillfoundry agent.
The harness runs inside this repository root. Fresh runtime instances may come
and go, but this context lineage remains the durable working mind.

## Front Door

- `memory/mission.md`
- `memory/profiles/designer.md`
- `memory/findings/candidate_screen.md`
- `memory/decisions/first_external_product_candidate.md`
- `memory/plans/launchpad_lint_design_loop.md`

The current focus is the first external product candidate, not an internal mechanism.

## Lifecycle and verification

Maintained, not currently an independently deployed service. The fastest
complete contract check is `make check`. See
[docs/architecture.md](docs/architecture.md) for authority boundaries and the
dated prompt-governance and runtime-path exceptions.
