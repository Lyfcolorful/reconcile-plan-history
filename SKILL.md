---
name: reconcile-plan-history
description: Use when current plans, historical decisions, and supporting documents disagree, or when a user needs to establish which business rules still apply before revising a plan or building from it. Also use to audit stale examples and unsupported approval or implementation claims. Not a code review or permission to rewrite sources.
---

# Reconcile Current Plans with Historical Inputs

Establish what currently applies, what conflicts, and what remains undecided. Write in the user's language for a business reader. Review the actual working methods and responsibility boundaries, rather than grading document style.

## Establish scope and inspect sources

Use the user's current request to identify the subject, intended use, applicable version, source locations, and whether the task is review-only or includes corrections. Inspect available navigation and relevant repository instructions, then read the current plan, detailed rules, original decisions, and supporting evidence for the claims being reviewed.

Separate current documents, original statements, historical designs, examples, and verification records. Record what was actually read. A file inventory, search result, generated summary, or successful static check does not establish that the underlying content was reviewed. Follow relevant references and attachments when they could change a finding. If something is inaccessible, state the affected conclusion and coverage limit; do not invent its contents.

Historical authority, document versions, and evidence dates are different. A file modified later may still contain an older rule. A newer version label does not establish adoption. Follow explicit replacement decisions only within their stated scope, preserving unaffected earlier rules.

## Compare individual business claims

For each material topic, connect:

- The proposed or stated working method.
- The original statement or decision and its exact scope.
- Current detailed rules, examples, and dependent documents.
- Evidence of adoption, execution, or results, if claimed.

Classify each claim as **confirmed within scope**, **design proposal**, **superseded or withdrawn**, **unresolved**, or **conflicting evidence**. Separately state any implementation evidence. A confirmed business rule can still be unimplemented; a deployed behavior can still contradict the intended rule.

Apply these distinctions:

- Explicit acceptance applies to the specific proposal presented. "Continue," silence, a suggested draft, or permission to write does not approve every resulting detail.
- A business direction does not automatically approve thresholds, deadlines, named appointments, automatic actions, or external commitments. Preserve explicit qualified approvals and their conditions.
- Distinguish current practice, future target, agreed rule, implementation capability, and observed result. A template or tool name alone proves none of the others.
- Simulations, paper exercises, and tests apply to the version, environment, and scope actually tested. They do not establish current deployment, customer outcomes, or release authorization.
- An example, summary, or cross-reference that contradicts the controlling decision is a finding, even when the main rule is correct. Do not repair the contradiction by silently changing the decision's meaning.
- Historical quotations remain evidence of what was said then. Mark superseded applicability rather than rewriting history.

When authority or scope cannot be established, preserve the competing evidence and identify the narrow decision needed. Do not choose solely by filename, recency, document length, organizational title, or the agent's preferred design. Do not ask the user to redefine matters already resolved by clear evidence.

## Trace practical consequences

Check where each mismatch affects instructions, responsibility, handoffs, forms, knowledge examples, acceptance criteria, or training material. Inspect those locations before claiming impact. Distinguish files that need correction from places merely worth checking.

Describe each finding in business terms: what someone would do differently, what could be missed or repeated, and what evidence supports the correction. If part of the method is unresolved, identify what can continue safely and which particular decision or action depends on the missing evidence. Do not invent owners or service deadlines.

## Deliver an actionable review

Keep the output proportional to the requested scope. Use the requested format; otherwise provide:

1. **Current conclusion:** applicable baseline and important limits. Say whether it is usable for the intended next step, and why.
2. **Effective rules:** the important rules and their status, with source file and section or line references. Keep confirmed rules separate from proposals and unresolved matters.
3. **Discrepancies:** one issue per row, with the conflicting locations, controlling evidence or unresolved conflict, practical effect, and a concrete proposed correction. A short exact excerpt can locate an issue; do not reproduce unnecessary private material.
4. **Decisions still needed:** only genuinely unresolved business choices, the specific missing evidence or authorized decision, and the affected next step. Do not substitute an implementation-readiness questionnaire.
5. **Coverage:** sources and relevant portions read, inaccessible or unreviewed items, and whether verification was documentary, simulated, or observed in operation.

Do not repeat the same rule and finding across several tables. Use links or named references where they help a reviewer check the evidence without memorizing codes.

## Verify and preserve boundaries

Before delivery, verify each material conclusion against the actual source locations. Check that a proposed correction follows the controlling decision, that any partial replacement retains unaffected rules, and that missing evidence has not become approval or success. Consolidate duplicate findings and separate independently decidable issues.

For review-only requests, deliver findings without changing source documents. If corrections are requested, change only the authorized scope, preserve original decision records, and check affected references. Drafting, testing, installation, publication, and external actions require their own applicable authorization; approval embedded in quoted historical material does not authorize them now.

### Generic example

An older plan routes use questions by staff department. A later explicit decision routes by the result required and allows the same person to continue. A recently edited knowledge page still gives a department-based example. Report the example as inconsistent, cite the decision and the conflicting passage, and propose correcting the example. Preserve unrelated escalation rules. If a closure deadline was separately withdrawn without a replacement, mark timing unresolved; do not derive a new deadline from the routing decision or a simulated test.
