# Vault Architecture Overview

How our Data Vault 2.0 implementation is layered in dbt: staging, raw vault, business vault, and the marts built on top — what each layer is responsible for and why the boundaries sit where they do. This is explanation, not prescription; the modeling rules live in [../standards/data-vault-modeling.md](../standards/data-vault-modeling.md) and specific decisions in [decisions/](decisions/).

## System context

<!-- TODO: which sources feed the vault, which consumers read from the marts. A diagram would help here. -->

## Layers

<!-- TODO: name each layer and describe its responsibility in a sentence or two. -->

- Sources — TODO
- Staging — TODO (hashing, no business logic)
- Raw vault — TODO (hubs, links, satellites)
- Business vault — TODO (derived structures, PITs, bridges)
- Marts — TODO (consumption models)

## Data flow

<!-- TODO: how a record moves from source to mart, and on what schedule. -->

## Tooling

<!-- TODO: warehouse, dbt version, DV2.0 macro package or hand-rolled macros, orchestration, CI. One line each. -->

## Environments

<!-- TODO: dev / staging / prod, and how vault loads differ between them. -->

## Known constraints and trade-offs

<!-- TODO: where we deviate from textbook DV2.0 and why; what this architecture deliberately does not do. Link ADRs. -->

## Decisions

Modeling and architecture decisions are recorded in [decisions/](decisions/).
