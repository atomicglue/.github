## Why
<!-- Linear issue link and one sentence on the problem this solves. -->
Linear: 

## What changed
<!-- 3 to 5 plain-language bullets. Describe behavior, not files. -->
-

## Risk tier
<!-- Check exactly one. High is required if this touches auth, client data,
payments, infra, env vars, dependencies, or the deploy pipeline. -->
- [ ] **Low**: copy, styles, content, or config with no behavior change
- [ ] **Standard**: new or changed behavior
- [ ] **High**: auth, client data, payments, infra, env vars, dependencies, deploy pipeline

## Reviewer checklist
<!-- Specific checks the reviewer must perform. Each one should be verifiable.
Bad: "Check that it works." Good: "On the preview, submit the contact form
and confirm the success message appears." -->
- [ ]
- [ ]

<!-- High risk only: the reviewer must also complete these. -->
- [ ] Read every file listed under "Files that matter"
- [ ] Left at least one written question or comment on the diff
- [ ] Confirmed the rollback plan below is workable

## Files that matter
<!-- Where the reviewer should spend their time. List files to skip too
(lock files, generated code, snapshots). -->
**Review:**
-

**Skip:**
-

## How to test
<!-- Preview URL and step-by-step instructions. -->
Preview:

1.

## Out of scope
<!-- What the reviewer should not spend time on in this PR. -->
-

## Rollback
<!-- How to undo this if it breaks production. -->
- [ ] Revert this PR
- [ ] Redeploy previous build in Vercel
- [ ] Other:
