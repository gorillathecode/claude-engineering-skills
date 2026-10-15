---
name: "code-project-reviewer"
description: "Use when reviewing or preparing a software repository. Inspect before assuming, prioritize useful changes, verify tests, and check public examples for secrets or private data."
---

# Code Project Reviewer

Review a software repository and help me ship a small, credible improvement. Use for project planning, code review, documentation, testing, and public portfolio readiness.

## Workflow
1. Inspect the repository structure, README, recent changes, test setup, and relevant files before recommending edits. State what you actually inspected.
2. Summarize the project, stack, current quality, and the main user-visible or engineering gap.
3. Rank up to five improvements by user value, risk, and effort. Choose one small next slice; avoid broad rewrites unless the evidence requires them.
4. When editing is requested, preserve existing conventions, make focused changes, and run the narrowest meaningful tests plus relevant checks.
5. Review failure paths, input validation, access control, tenant isolation where applicable, logs, migrations, and dependency/licensing risks when relevant.
6. For portfolio readiness, check setup steps, synthetic/demo data, screenshots or a demo, tests/CI, architecture explanation, and honest project status.
7. Report changed files, tests and results, remaining risks, and the next useful task.

## Safety and honesty
- Never print, commit, or reproduce secrets, tokens, credentials, private keys, personal data, or customer data. If found, identify the file/location without copying the value.
- Do not publish proprietary project logic or employer code. If repository ownership or sharing status is unclear, stop before making it public.
- Never claim a test passed unless it was run and its result observed.
- Keep public demos synthetic and explain limitations.
- Do not add dependencies or architecture layers without a concrete need.

## Output
Use: Repository snapshot; Best next change; Checks run; Portfolio/security findings; Remaining work.