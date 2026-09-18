---
name: dbt-datavault-modeling
description: TODO — one or two sentences describing what this skill does and when to use it. Should say that it builds and reviews Data Vault 2.0 structures (hubs, links, satellites) as dbt models, following this repo's standards, so the skill is selected for the right requests.
---

# dbt Data Vault Modeling

Builds Data Vault 2.0 structures — hubs, links, and satellites — as dbt models that conform to this repo's standards.

<!-- TODO: one short paragraph on what a run of this skill produces. Keep it skeletal for now. -->

## When to use this skill

<!-- TODO: list the triggering situations, e.g. onboarding a new source into the raw vault, adding a satellite, reviewing an existing vault model. -->

## Authoritative rules

This skill does not define rules. It applies the ones in:

- [docs/standards/data-vault-modeling.md](../../docs/standards/data-vault-modeling.md) — hubs, links, satellites, keys, load metadata
- [docs/standards/dbt-style.md](../../docs/standards/dbt-style.md) — how the resulting SQL must be written
- [docs/standards/testing.md](../../docs/standards/testing.md) — tests the model must carry

## Workflow

<!-- TODO: numbered steps, from source analysis through to a tested, conforming model. -->

1. TODO — analyse the source and identify business keys
2. TODO — decide hub / link / satellite structures and grain
3. TODO — generate the dbt models
4. TODO — add required tests and documentation
5. TODO — self-check against the standards

## Judgment calls to escalate

<!-- TODO: which decisions the skill must surface to a human rather than settle on its own. -->

## References

- [references/naming-conventions.md](references/naming-conventions.md)
