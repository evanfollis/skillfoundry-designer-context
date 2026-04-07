# Launchpad Lint Design Loop

## Goal

Produce a builder-ready design brief for the first external product candidate.

## Product Shape

`launchpad-lint` helps a builder audit a candidate MCP server and generate the minimal
launch package needed for a credible first marketplace submission.

## Proposed V1 Tool Surface

### `audit_launch_readiness`

Input:

- server name
- tool names and descriptions
- optional README or listing draft
- optional endpoint metadata

Output:

- launch blockers
- clarity issues
- missing operator information
- suggested fixes

### `draft_launch_package`

Input:

- validated tool surface
- target user
- constraints and positioning hints

Output:

- short description
- long description
- example prompts
- explicit limits
- pricing questions to resolve

## Success Metrics

- users can understand what is missing before launch in one pass
- generated launch package needs only light editing
- output improves install-to-first-value clarity for the chosen ICP

## Kill Criteria

- if the output is mostly generic marketing filler
- if the audit cannot say anything useful without deep custom context
- if users still need substantial manual rewriting before submission

## Downstream Handoff

If this brief survives review, hand it to:

- `builder` for implementation
- `growth` for launch artifact refinement
- `pricing` for price framing and experiment shape
