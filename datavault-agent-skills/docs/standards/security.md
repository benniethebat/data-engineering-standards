# Security and Data Handling Standard

Rules for handling sensitive data inside the vault — where PII may live in satellites, how it is masked or separated, plus access control and secrets management for the dbt project. This document is the source of truth — process docs and skills link here rather than restating any of it.

Rules are written as do/don't pairs.

## Data classification

<!-- TODO: the classification tiers in use and what falls into each. -->

- Do: TODO
- Don't: TODO

## Sensitive data in vault structures

<!-- TODO: PII in business keys and hash keys, separating sensitive attributes into their own satellites, masking, tokenisation, what may appear in dev environments. -->

- Do: TODO
- Don't: TODO

## Secrets and credentials

<!-- TODO: where warehouse credentials and dbt profiles live, rotation, what must never be committed. -->

- Do: TODO
- Don't: TODO

## Access control

<!-- TODO: warehouse roles by layer, least privilege, how access is requested and reviewed. -->

- Do: TODO
- Don't: TODO

## Retention and deletion

<!-- TODO: retention periods and how deletion requests are handled against an insert-only vault. -->

- Do: TODO
- Don't: TODO

## Incident response

<!-- TODO: what to do on a suspected exposure, and who to tell. -->

## AI agents

<!-- TODO: what source data, schemas, or sample rows may be shared with AI tooling, and what may not. -->

- Do: TODO
- Don't: TODO
