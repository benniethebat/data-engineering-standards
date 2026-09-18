# dbt and SQL Style Standard

Code formatting and structural conventions for the SQL and dbt that implements our Data Vault: layout, CTE structure, naming, and file organisation. This document is the source of truth — process docs and skills link here rather than restating any of it.

Rules are written as do/don't pairs. Each rule should be checkable by a human reviewer or a linter.

## How to read this document

- **Do** — required.
- **Don't** — prohibited.
- **Prefer** — a default that may be overridden with a note explaining why.

## Formatting

<!-- TODO: keyword case, indentation, line length, trailing vs leading commas, blank lines. -->

- Do: TODO
- Don't: TODO

## CTEs and query structure

<!-- TODO: import CTEs, naming, ordering, the shape of a staging model that produces hash keys, final select. -->

- Do: TODO
- Don't: TODO

## Naming

<!-- TODO: models, columns, sources, macros, tests. For vault-object names, cross-link data-vault-modeling.md rather than repeating them here. -->

- Do: TODO
- Don't: TODO

## Model configuration

<!-- TODO: where config lives, materializations for vault objects (insert-only vs incremental), tags. -->

- Do: TODO
- Don't: TODO

## Jinja and macros

<!-- TODO: when a vault macro is warranted, how macro calls are formatted, arguments per line. -->

- Do: TODO
- Don't: TODO

## Documentation and YAML

<!-- TODO: required model and column descriptions, schema.yml layout, doc blocks. -->

- Do: TODO
- Don't: TODO

## Tooling

<!-- TODO: the formatter/linter that enforces this and how to run it. -->
