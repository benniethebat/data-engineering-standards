# 02 — Design

Deciding the vault design before any model is written: which hubs, links, and satellites the change requires, what the business keys and grain are, and which decisions need recording. This document describes the procedure only; the modeling rules themselves live in [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md).

## Entry criteria

<!-- TODO: what must come out of [01-planning.md](01-planning.md). -->

## Steps

<!-- TODO: fill in each step. -->

1. Source profiling — TODO (volumes, keys, change behaviour, deletes)
2. Identify business keys and confirm them with the business — TODO
3. Determine hubs, links, and link grain — TODO
4. Determine satellite splits — TODO
5. Classify sensitive attributes — per [../standards/security.md](../standards/security.md)
6. Check the design against [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md)
7. Record any decision that constrains future modeling as an ADR — see [../architecture/decisions/0001-template.md](../architecture/decisions/0001-template.md)
8. Design review — TODO who, TODO format

## Artifacts produced

<!-- TODO: e.g. a vault design sketch, source-to-target mapping, one or more ADRs. -->

## Exit criteria

<!-- TODO: what must be true to move to [03-implementation.md](03-implementation.md). -->

## Applicable standards

- Modeling: [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md)
- Sensitive attributes in the design: [../standards/security.md](../standards/security.md)
