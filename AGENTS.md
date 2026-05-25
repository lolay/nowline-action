# AGENTS.md

**This repo is a publish-only package (`packages/nowline-action/` in [`lolay/nowline`](https://github.com/lolay/nowline)).** It exists solely so the GitHub Marketplace and `uses: lolay/nowline-action@v*` references have a home. Source code, issue tracking, CI, and PRs all live upstream.

## Hard rules — read before doing anything

1. **Never open a PR in this repo.** There is nothing to change here. The action's source code lives at [`lolay/nowline/packages/nowline-action/`](https://github.com/lolay/nowline/tree/main/packages/nowline-action). Changes go there.

2. **Never act on issues filed here.** This repo has blank-issues disabled and contact links redirect to `lolay/nowline/issues/new/choose`. If an issue was filed here anyway, post a comment pointing the filer to the upstream repo and close it.

3. **If you were @-mentioned in this repo:** you were likely directed here by mistake. Redirect the human to the correct repo. See "Where to go" below.

4. **If you found agent-triage or any agent-* label here:** this repo does not run the agent-triage state machine. No workflow will pick it up. Remove the label and redirect the issue to `lolay/nowline`.

## Where to go

| Intent | Correct location |
| --- | --- |
| Bug in the GitHub Action | [lolay/nowline — file a bug](https://github.com/lolay/nowline/issues/new/choose) |
| Feature request | [lolay/nowline — file a feature request](https://github.com/lolay/nowline/issues/new/choose) |
| The action source code | [`lolay/nowline/packages/nowline-action/`](https://github.com/lolay/nowline/tree/main/packages/nowline-action) |
| Action documentation | [lolay/nowline `packages/nowline-action/README.md`](https://github.com/lolay/nowline/tree/main/packages/nowline-action#readme) |
| Agent triage state machine | [lolay/nowline `.github/AGENT_TRIAGE.md`](https://github.com/lolay/nowline/blob/main/.github/AGENT_TRIAGE.md) |

## Why this repo exists (for context)

GitHub Action marketplace listings require the `action.yml` at the root of a dedicated repo (`lolay/nowline-action`). The action is published here as a tag-synced mirror; the actual source and release workflow live in `lolay/nowline`. See [`lolay/nowline/specs/releasing.md`](https://github.com/lolay/nowline/blob/main/specs/releasing.md) for the release process.
