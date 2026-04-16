# Pull Request Review Template

## What Changed

- Summary of the change:
- Current behavior:
- New behavior:
- Why the change was needed:

## Why This Repo Owns It

- Repo owner:
- Why this repository is the correct boundary:
- Any nearby responsibilities that were deliberately left out:

## Issue and Planning Links

- Primary issue:
- Parent issue:
- Child issues:
- Related docs / planning refs:

## Affected Contracts

- [ ] No contract changes
- [ ] API contract changed
- [ ] Shared type / schema changed
- [ ] Response shape changed
- [ ] Auth / permission behavior changed
- [ ] Data / schema behavior changed

### Contract Notes
Describe exactly what changed, who consumes it, and whether compatibility is preserved.

## Downstream Repos Affected

- [ ] None
- [ ] ai-orchestrator
- [ ] discord-bot
- [ ] engineering-planning
- [ ] agm-legacy
- [ ] company-website
- [ ] customer-frontend
- [ ] manager-frontend
- [ ] platform-api
- [ ] platform-infra
- [ ] platform-shared

### Downstream Impact Notes
Explain any required follow-up PRs, release ordering, or compatibility constraints.

## Tests Run

- Unit:
- Integration:
- E2E:
- Manual Verification:
- Migration / Rollback Validation:

## Screenshots / UI Evidence

For frontend work, include before/after screenshots or short screen recordings.

## Manual Verification Steps

1.
2.
3.

## Rollback Notes

- How to roll back:
- What would need to be reverted:
- Any schema / data / config risks:
- Can this be disabled without revert?: yes | no

## Migration Notes

- Is this preserving legacy behavior during extraction?: yes | no
- Any temporary adapters or compatibility shims?:
- Any known blockers still remaining?:
- Does this reduce coupling, preserve it temporarily, or create new coupling?:

## Deployment / Release Notes

- Can this ship alone?: yes | no
- Required release order:
- Staging soak required?: yes | no
- Rollback rehearsal required?: yes | no
- Env / secret changes required?: yes | no

## Boundary Check

- [ ] No business logic was introduced into a frontend repo
- [ ] No direct DB access was introduced outside backend ownership
- [ ] No shared repo convenience abstraction was added without justification
- [ ] No hidden cross-repo dependency was introduced
- [ ] Acceptance criteria from the issue are satisfied
- [ ] Required tests from the issue are satisfied
