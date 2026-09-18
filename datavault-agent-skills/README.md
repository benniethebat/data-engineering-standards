# datavault-agent-skills

A Data Vault 2.0 modeling toolkit for dbt, packaged as Agent Skills.

The substance here is the DV2.0 practice: how we pick business keys, set link grain, split satellites, derive hash keys, and test the result in dbt. The `AGENTS.md` and `skills/` structure is just how that practice gets delivered to an AI coding agent — the same documents are written to be read by people.

<!-- TODO: one or two sentences — which team owns this and which dbt project(s) it governs. -->

## Start here

| You are | Read |
| --- | --- |
| An AI coding agent | [AGENTS.md](AGENTS.md) |
| A human contributor | [CONTRIBUTING.md](CONTRIBUTING.md), then [docs/README.md](docs/README.md) |
| Building a hub, link, or satellite | [skills/dbt-datavault-modeling/](skills/dbt-datavault-modeling/) |
| Looking for a modeling rule | [docs/standards/data-vault-modeling.md](docs/standards/data-vault-modeling.md) |
| Shipping a vault change | [docs/process/](docs/process/) |

## What's in here

- **Skills** — [skills/](skills/): the modeling method in a form an agent can execute.
- **Standards** — [docs/standards/](docs/standards/): the rules, written as do/don't pairs. Source of truth.
- **Architecture** — [docs/architecture/](docs/architecture/): how our vault is layered, and the decisions behind it.
- **Process** — [docs/process/](docs/process/): planning → design → implementation → review → release for a vault change.

## Scope

<!-- TODO: warehouse, dbt version, DV2.0 variant/conventions followed (e.g. automate-dv or hand-rolled macros), and what is explicitly out of scope — mart design, ingestion, orchestration. -->

## Status

Skeleton. Every file is a placeholder awaiting content.

## License

TODO — see [LICENSE](LICENSE); no license has been chosen yet.
