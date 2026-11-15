# bolt.diy personal fork handover

Last updated: **15 November 2026, Australia/Brisbane**.

## Current work and immediate next action

The current task is to establish portable project context and a required session read/update workflow.
This is a documentation checkpoint prepared from the default-branch source, preserving existing project rules.
No application source, dependency, provider setting or production data was changed by this inventory.

**Next concrete action:** Compare the fork's current main with the intended upstream, read CONTRIBUTING.md and PROJECT.md, then choose a scoped fork-maintenance task.

**Repository state:** [InfoAddict/bolt.diy](https://github.com/InfoAddict/bolt.diy), default branch `main`.
The source SHA below predates this documentation change. The commit containing this file identifies its documentation revision; verify the current remote before assuming a local checkout is synced. No deployment result is claimed.

## Purpose and source map

Fork of the open-source browser AI coding application bolt.diy.

**Declared stack:** Remix/React, TypeScript, Vite, WebContainers and multiple AI adapters; optional Electron and Docker packaging are declared.

- app/: application routes, editor and AI integration source.
- functions/: Cloudflare-facing runtime surface.
- electron/ and scripts/: desktop and maintenance tooling.

## Source checkpoint and milestones

- Source repository: [InfoAddict/bolt.diy](https://github.com/InfoAddict/bolt.diy).
- Visibility at inventory: public.
- Default branch: `main`.
- Exact pre-documentation head: `71609dd99caeb32f179ccf4a98fda82833afd233`.
- Source tree SHA: `41a2e1b8d4297814bfe84506cba666ac73519af8`.
- These identify the source inspected, not a newly verified deployment.

- [71609dd](https://github.com/InfoAddict/bolt.diy/commit/71609dd99caeb32f179ccf4a98fda82833afd233) (2025-06-04, UTC): Merge branch 'aigem:main' into main.
- [05d7ef0](https://github.com/InfoAddict/bolt.diy/commit/05d7ef0ab59abf586e7ce7c5b016c2cc861e2fee) (2025-05-27, UTC): Update README.md.
- [b6992fe](https://github.com/InfoAddict/bolt.diy/commit/b6992fe3a9ea1dfe7fcf7d6aff71690eef213161) (2025-05-26, UTC): Merge pull request #1736 from stackblitz-labs/revert-1725-fix/docker-oom.
- [c64f69b](https://github.com/InfoAddict/bolt.diy/commit/c64f69b01d9af843bee593492e51899d88080dd0) (2025-05-26, UTC): Revert "fix: increase Node.js memory limit in Docker build".
- [c008c7a](https://github.com/InfoAddict/bolt.diy/commit/c008c7a557cdb1af554f6f9ee8d4434dc334a491) (2025-05-26, UTC): Merge pull request #1725 from ssuvamm/fix/docker-oom.

Commit titles report recorded changes. They are not fresh test, CI, browser or provider results.

## Existing decisions and boundaries

- This is a personal fork of aigem/bolt.diy, not a newly created upstream contribution.
- CONTRIBUTING.md requires feature/fix branches from main and a maintainer-reviewed PR.
- Keep provider credentials in ignored local configuration; a deploy script is not release authority.

Preserve the relevant existing instructions and release route. This checkpoint does not create a portfolio-wide publishing policy.

## Outstanding work and uncertainty

- No personal feature task was established in the reviewed history.
- The latest commits are upstream merge/documentation/build-memory history from May/June 2025.
- Review divergence and contribution requirements before proposing upgrades or a fork-specific change.

No identifiable project-specific chat was found in the reviewed history inventory for this repository.
That is a coverage limit, not proof that no other chat, local work or decision exists.
The matching local checkout was clean on `main` at `71609dd99caeb32f179ccf4a98fda82833afd233`, matching this remote source snapshot, in the 15 November inventory. Recheck before editing.

## Portable source references

- [README.md](README.md).
- [CONTRIBUTING.md](CONTRIBUTING.md).
- [PROJECT.md](PROJECT.md).
- [FAQ.md](FAQ.md).
- [package.json](package.json).

Existing specialised status/design/operating documents remain supporting records; they were not replaced.
Read linked documents for the selected task and reconcile their dates against current source.

## Evidence and validation limits

- Fresh authenticated GitHub reads established metadata, branch source, root paths and the commit history above.
- Selected source documentation and declared manifests informed this record.
- No application build, test, dependency install, rendered-browser check or live-provider workflow was run.
- Deployment, credentials, service readiness and current runtime behaviour remain unverified here.
- README completion labels and older evidence retain their original dates and scope.
- Recheck the branch head before publishing, and merge concurrent handover changes instead of overwriting them.

## Resume sequence

1. Read [AGENTS.md](AGENTS.md) and this handover, then the linked project contracts relevant to the request.
2. Inspect the actual branch/worktree and current remote source. Preserve unrelated and untracked work.
3. Compare the fork's current main with the intended upstream, read CONTRIBUTING.md and PROJECT.md, then choose a scoped fork-maintenance task.
4. Verify only the selected task with appropriate checks; obtain any release authority required by the current request.
5. Update this handover before finishing, distinguishing local, committed, pushed, deployed and observed results.

## Session log

### 15 November 2026

- Requested: portable handover and required session continuity.
- Prepared: this source-based handover and the shared workflow in AGENTS.md; existing instruction text retained.
- Checked: remote source metadata, commit messages and available project documents.
- Not checked: application/runtime behaviour, provider/deployment state or other machines. Local status is limited to the dated inventory above.
- Next: Compare the fork's current main with the intended upstream, read CONTRIBUTING.md and PROJECT.md, then choose a scoped fork-maintenance task.

## Resume prompt

> Read AGENTS.md and handover.md. Check the current source and worktree, preserve other work, and continue only the next scoped task. Treat historical claims as dated evidence. Update handover.md with actual checks and unfinished work before finishing.
