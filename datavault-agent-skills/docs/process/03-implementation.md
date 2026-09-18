# 03 — Implementation

Building the vault models: writing the staging, hub, link, and satellite models in dbt, adding their tests and documentation, and getting the change into a reviewable state. This document describes the procedure only; how the SQL must be written lives in [../standards/dbt-style.md](../standards/dbt-style.md).

## Entry criteria

<!-- TODO: what must come out of [02-design.md](02-design.md). -->

## Steps

<!-- TODO: fill in each step. -->

1. Branch — TODO naming, see [../../CONTRIBUTING.md](../../CONTRIBUTING.md)
2. Build staging models with hash keys — apply [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md)
3. Build hubs, links, and satellites — the [dbt-datavault-modeling skill](../../skills/dbt-datavault-modeling/SKILL.md) packages this method
4. Format to [../standards/dbt-style.md](../standards/dbt-style.md)
5. Add the required tests — per [../standards/testing.md](../standards/testing.md)
6. Document models and columns — TODO what is required
7. Run local checks — TODO exact commands
8. Update [../../CHANGELOG.md](../../CHANGELOG.md) under Unreleased
9. Open a PR — TODO

## Working with AI agents

Agents should follow [../../AGENTS.md](../../AGENTS.md) and use the skill rather than reconstructing the method.

<!-- TODO: what agents may do here unattended, and what a human must verify — business key selection and link grain are likely candidates. -->

## Exit criteria

<!-- TODO: what must be true to move to [04-review.md](04-review.md). -->
