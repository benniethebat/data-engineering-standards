# AGENTS.md

Instructions for AI coding agents working in this repository. Humans should start with [README.md](README.md) and [CONTRIBUTING.md](CONTRIBUTING.md).

## What this repo is

This repo encodes our Data Vault 2.0 modeling practice for dbt — the modeling rules, the SQL/dbt formatting conventions, the tests a vault model must carry, and the lifecycle a vault change moves through — and packages it as Agent Skills so an agent can apply it directly.

<!-- TODO: one paragraph — which dbt project(s) and warehouse these apply to, and whether this repo ships any code beyond the skills. -->

## Read before building any vault model

Documents in `docs/standards/` are the **source of truth**. If a process doc, a skill, or a comment in code disagrees with a standards doc, the standards doc wins.

1. [docs/standards/data-vault-modeling.md](docs/standards/data-vault-modeling.md) — hub/link/satellite rules, business keys, hashing, load metadata
2. [docs/standards/dbt-style.md](docs/standards/dbt-style.md) — SQL and dbt code formatting conventions
3. [docs/standards/testing.md](docs/standards/testing.md) — tests every vault model must carry
4. [docs/standards/security.md](docs/standards/security.md) — sensitive data in vault structures, secrets, access

## Skills

Use the skill rather than reconstructing the method from the docs:

- [skills/dbt-datavault-modeling/](skills/dbt-datavault-modeling/) — build hubs, links, and satellites in dbt

Skills apply the standards; they never redefine them.

## Repository map

<!-- TODO: keep this in sync with docs/README.md -->

- `skills/` — Agent Skills that package the DV2.0 modeling method
- `docs/standards/` — do/don't rules for DV2.0 in dbt; source of truth
- `docs/architecture/` — how our vault is layered, plus ADRs for modeling decisions
- `docs/process/` — planning through release for a vault change; references the standards rather than restating them
- `docs/glossary.md` — DV2.0 vocabulary as we use it

## Working agreements

<!-- TODO: fill in. Suggested items to decide on: -->
- Branch naming: TODO
- Commit message format: TODO
- What an agent may change unattended vs. what needs human sign-off (e.g. business key selection): TODO
- Commands to run before opening a PR (lint, `dbt build`, etc.): TODO

## When you are unsure

Business key selection, link grain, and satellite splits are modeling judgments, not mechanical ones.

<!-- TODO: state the escalation path — open an issue, ask in a channel, propose an ADR. -->
