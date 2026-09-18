# 04 — Review

How a vault change is reviewed and approved before release. This document describes the procedure only; reviewers check the change against [../standards/](../standards/), which is the source of truth for what a conforming vault model looks like.

## Entry criteria

<!-- TODO: what must be true before review starts — CI green, PR template filled in. -->

## What reviewers check

Reviewers verify conformance to the standards; they do not invent rules in review. If a rule is missing, propose it as a change to [../standards/](../standards/).

- Modeling: [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md) — business keys, link grain, satellite splits, hashing, load metadata
- Style: [../standards/dbt-style.md](../standards/dbt-style.md)
- Tests: [../standards/testing.md](../standards/testing.md)
- Security: [../standards/security.md](../standards/security.md)

## Steps

<!-- TODO: fill in each step. -->

1. Automated checks — TODO what must pass
2. Assign reviewers — TODO how many, see [../../CODEOWNERS](../../CODEOWNERS)
3. Review pass — TODO expected turnaround
4. Address feedback — TODO
5. Approve and merge — TODO who merges

## Reviewing agent-authored changes

<!-- TODO: any additional scrutiny that applies — e.g. always re-check business key choice and grain by hand. -->

## Exit criteria

<!-- TODO: what must be true to move to [05-release.md](05-release.md). -->
