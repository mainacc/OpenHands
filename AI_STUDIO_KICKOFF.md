# AI Developer Studio — Phase 0 Kickoff

Use `MASTER_BUILD_PLAN.md` as the project's governing specification. **Execute Phase 0 only.**

Audit the current OpenHands fork before changing the architecture. Map the React frontend, Electron desktop app, OpenVSCode editor, OpenHands SDK/Agent Server, GitHub workflows, security boundaries, licensing, and model-provider integrations (including Mistral).

Run available builds and tests, then prove the smallest end-to-end workflow: open a repository, inspect/edit code, delegate one isolated AI coding task, run relevant tests, review the diff, and prepare a pull request.

Produce `docs/PHASE_0_AUDIT.md` containing:
- verified module map, execution architecture and code-reuse recommendations;
- exact build/test commands, results, blockers and evidence;
- security risks (secrets, sandboxing, editor isolation and approvals);
- recommended first working vertical slice, with acceptance tests;
- explicit **go/no-go** assessment and Phase 1 task breakdown.

**Rules:** Do not rewrite the UI or agent engine yet. Do not assume existing integrations work until verified. Keep all source changes on a feature branch, avoid destructive operations or live deployments, never commit credentials, and submit results as a pull request for review.
