# Copilot Instructions

These instructions apply to all AGM-Report repositories. Each repository also has its own `.github/copilot-instructions.md` with repo-specific rules — read both.

Always read and follow:
1. `README.md` for the active repo
2. `AGM_AGENT_MASTER_README.md` from planning / project context
3. `REPO_MAP.md` and `BOUNDARIES_ALL.md` when ownership is unclear
4. The active GitHub issue acceptance criteria, risks, required tests, and out-of-scope notes

Non-negotiable rules:
- Stay within repo ownership.
- Do not invent architecture rules locally.
- Keep changes small, reviewable, and testable.
- Surface missing dependencies instead of silently crossing boundaries.

## Completion Reporting — Required

When you finish work on a GitHub issue you MUST post your completion report as a comment on BOTH the original GitHub issue AND the pull request. Do not rely on your session log as the only record of completion. The automated review system reads issue comments and PR comments — if the comment is not posted in both places, your work will not be reviewed and the ticket will stall.

## Linked Issue
- Issue: #ISSUE_NUMBER

## Summary
- What this PR changes
- Why the change exists
- What repo-local responsibility it fulfills

## Scope Alignment
- In scope:
  - ...
- Out of scope:
  - ...

## Files / Surfaces Changed
- ...
- ...

## Acceptance Criteria Mapping
| Criterion | Status | Evidence in PR |
|-----------|--------|----------------|
| {criterion} | met / partially met / not met | {file, run, or explanation} |

## CI Evidence
- Workflow run:
- Workflow name:
- Job name(s):
- Result:
- Notes:

## Manual / Runtime Validation
- What was validated outside CI:
- What was not validated:
- Why:

## Deviations From Ticket
- None.

## Risks
- ...

## Rollback / Disable Plan
- ...

## Open Gaps
- None

---
