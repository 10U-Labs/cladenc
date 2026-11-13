---
name: push-to-main
description: "In this repo, commit and push directly to main — no feature branches or PRs"
metadata:
  node_type: memory
  type: feedback
  originSessionId: 92d16771-d8b4-4ee4-8f39-ae96be264e22
  modified: 2026-11-13T04:33:37.142Z
---

Commit and push directly to `main`; don't create feature branches or open PRs.

**Why:** User's stated workflow for this repo ("we push to main").

**How to apply:** When asked to commit/push, stay on `main` and `git push origin main`. This overrides the default "branch first if on the default branch" guidance. Still only commit/push when asked.
