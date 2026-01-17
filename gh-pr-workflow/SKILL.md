---
name: gh-pr-workflow
description: GitHub CLI pull request creation and formatting. Use when asked to create PRs, generate PR titles/descriptions, add reviewers/labels, or troubleshoot gh auth.
---

# GitHub PR Workflow

## Overview

Create PRs with GitHub CLI using conventional titles and a consistent description template. Ask for missing details (base branch, reviewers, labels) only when needed.

## Prereqs

- `gh --version`
- `gh auth status` (or `gh auth login`)
- Branch pushed to remote

## Basic PR
```
gh pr create --title "type(scope): short description" --body "Detailed description"
```

## Draft PR
```
gh pr create --draft --title "wip: short description" --body "Work in progress"
```

## With reviewers/labels/base
```
gh pr create --base develop --title "fix(scope): short description" --body "Details" --reviewer @username --label bug,urgent
```

## PR description template (raw markdown)

When asked to generate PR content, output raw markdown exactly using this template:
```
## Summary
[1-2 sentences: what changed and why]

## High-Level Changes
- [Change 1]: [user-facing or architectural impact]
- [Change 2]: [impact]

## Detailed Implementation
- [Component Architecture]: [new/changed components]
- [State Management & Logic]: [state/data/validation changes]
- [Dependencies]: [new/updated packages]

## Test Plan
- [ ] Manual test step 1
- [ ] Manual test step 2
- [ ] Automated tests pass
```

## Troubleshooting

- Branch not on remote:
  - `git push -u origin <branch>`
- No commits to PR:
  - `git log main..HEAD`
  - `git status -sb`
- GH auth issues:
  - `gh auth status`
  - `gh auth login`
