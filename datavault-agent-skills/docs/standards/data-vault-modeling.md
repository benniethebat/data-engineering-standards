# Data Vault 2.0 Modeling Standard

The core standard of this repo: what qualifies as a hub, link, or satellite; how business keys are chosen; how hash keys and hash diffs are derived; what load metadata every structure carries; and what may live in the raw vault versus the business vault. This document is the source of truth for modeling decisions — process docs and skills link here rather than restating any of it.

Rules are written as do/don't pairs.

## Scope

<!-- TODO: which layers this governs, which DV2.0 conventions we follow, and what is deliberately out of scope (e.g. mart design). Note any deliberate deviation from textbook DV2.0. -->

## Hubs

<!-- TODO: what earns a hub, business key selection and grain, required columns, multi-source hubs. -->

- Do: TODO
- Don't: TODO

## Links

<!-- TODO: grain, degenerate fields, same-as links, hierarchical links, driving keys, unit-of-work. -->

- Do: TODO
- Don't: TODO

## Satellites

<!-- TODO: splitting by source and rate of change, hash diff, effectivity satellites, multi-active satellites, deletes. -->

- Do: TODO
- Don't: TODO

## Keys and hashing

<!-- TODO: hash algorithm, column concatenation order, casing, trimming, delimiters, null and empty-string handling, zero keys. -->

- Do: TODO
- Don't: TODO

## Load metadata

<!-- TODO: load date/timestamp, record source, batch identifiers, and where they are set. -->

- Do: TODO
- Don't: TODO

## Loading patterns

<!-- TODO: insert-only, idempotency, restartability, late-arriving data. -->

- Do: TODO
- Don't: TODO

## Raw vault vs business vault

<!-- TODO: what business logic is allowed where; PITs and bridges. -->

- Do: TODO
- Don't: TODO

## Related

- Formatting of the resulting SQL: [dbt-style.md](dbt-style.md)
- Required tests: [testing.md](testing.md)
- Sensitive attributes in satellites: [security.md](security.md)
- Naming quick reference: [../../skills/dbt-datavault-modeling/references/naming-conventions.md](../../skills/dbt-datavault-modeling/references/naming-conventions.md)
