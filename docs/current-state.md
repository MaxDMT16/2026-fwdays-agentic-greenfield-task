# `jarsplit` — current state

Tracks the last action taken in this repo, so the next agent or human knows
what happened and what to do next. Update this after completing a unit of work.

## Last action

**2026-07-01T00:00:00+00:00** — Wrote
[openspec-capability-plan.md](openspec-capability-plan.md): split the 38
requirement IDs in [product-requirements.md](product-requirements.md) into 6
OpenSpec capabilities (`plan-parsing`, `mono-client`, `jar-matching`,
`link-generation`, `output-reporting`, `cli-orchestration`) with a
dependency-ordered implementation sequence and a full ID-to-capability
traceability appendix. No code exists yet; `openspec/specs/` and
`openspec/changes/` are still empty.

## Next step

Run `openspec new change "add-plan-parsing"` (or the `openspec-propose`
skill) to start Phase 1 of the capability plan — `plan-parsing` and
`mono-client` can be worked in parallel, in either order.
