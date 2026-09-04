# Agent operating profile

This file adds repository-wide agent behavior without changing the project's purpose, canon, accepted decisions, or narrower directory instructions.

## Authority

Resolve work using the repository's existing authority order. An authorized user's explicit request and accepted project canon or decisions govern within their stated scope. More specific `AGENTS.md`, `CLAUDE.md`, skill, or task-local instructions apply only inside their scope and do not silently expand authority. External model or vendor guidance is implementation evidence, not project authority. Record conflicts and provenance instead of guessing them away.

## Execution and escalation

- Carry sufficiently specified, already-authorized, reversible work to a reviewable result. Do not stop at a plan or repeat a confirmation that the current request already resolved.
- Escalate when progress requires a project-purpose, authority, or value choice; an irreversible high-risk action; unavailable decision-critical evidence; or non-convergence. Complete other authorized preparation first when feasible.
- Preserve any project-required Audit → Prototype/Spike → Contract → Production sequence. Guidance in this file never authorizes skipping a gate or treating research/proposal output as Production approval.

## Validation, delegation, and reasoning

- Validate in proportion to the changed contract and risk. After applicable checks pass, broaden or repeat them only for a new change, failure, or unresolved concern.
- Parallelize independent evidence gathering, implementation, or validation only when the runtime supports it and doing so improves time or quality. Serialize authority, Contract, Production, and risk-acceptance decisions; agents do not create authority by consensus.
- Where supported, use lower reasoning effort for routine work and increase it for complex design, authority conflict, or failure analysis. Do not hard-code maximum effort for all tasks.

## OpenAI workflows and reporting

For a direct OpenAI tool workflow, verify current Responses API, tool-calling, model, reasoning, and parameter compatibility before changing implementation. Async tools, mid-turn steering, caching, or compaction are candidate mechanisms and still pass through the project's normal adoption gates.

Reports distinguish observation, inference, proposal, and human decision; record source and observation time; list applied changes and remaining gaps; and preserve `PASS / FAIL / UNVERIFIED`. Never convert unknown, unobserved, or partial results into success or zero.

