# Reconcile Plans and History

An agent skill for establishing which business rules currently apply when plans, historical inputs, examples, and verification records disagree.

Use it before revising an operating plan, preparing implementation inputs, or building a business review form from a document collection.

## What it does

- Distinguishes explicit decisions from proposals, superseded rules, and unresolved questions.
- Checks stale examples and dependent documents against the controlling evidence.
- Separates agreement on a business rule from actual implementation and observed results.
- Produces actionable findings with source locations, consequences, and proposed corrections.
- Discloses reading coverage and inaccessible evidence.

It does not treat the latest edit date as authority, interpret "continue" as blanket approval, or rewrite source documents during a review-only task.

## Use

Provide the current plan, historical decisions, relevant supporting materials, intended next step, and any version or scope constraints. Make this folder available through the skill-loading mechanism supported by your agent environment.

Example request:

> Use $reconcile-plan-history to compare the current process plan with its original decisions and historical notes. Identify applicable rules, stale examples, unresolved decisions, and concrete corrections. Review only; do not change source files. Explain the findings for a nontechnical business owner.

No scripts, credentials, external connectors, or runtime dependencies are required by this package. The agent uses available file-reading and document tools. It should disclose any sources or formats it cannot inspect.

## Package

```text
reconcile-plan-history/
|-- SKILL.md
`-- README.md
```

The generic example is contained in `SKILL.md`. No original business plans, customer records, private conversations, local verification logs, or machine-specific paths are included.

## Scope of assurance

This skill supports evidence-based document review. Its output does not certify deployment, approve a policy, grant an external team responsibility, or prove customer outcomes. Source corrections and external actions remain subject to the user's actual request and authorization.
