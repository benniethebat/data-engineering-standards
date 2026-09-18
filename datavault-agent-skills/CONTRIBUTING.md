# Contributing

How to propose and land a change to the Data Vault 2.0 standards, skills, and process docs in this repo. This file covers the mechanics; the lifecycle for a vault modeling change itself lives in [docs/process/](docs/process/).

## Before you start

<!-- TODO: prerequisites — dbt project access, warehouse access, local tooling. -->

## Making a change

<!-- TODO: fill in each step. -->

1. Branch — TODO naming convention
2. Write — follow [docs/standards/](docs/standards/); do not restate rules in process docs or skills, link to them
3. Commit — TODO message format
4. Open a PR using [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md)
5. Review — see [docs/process/04-review.md](docs/process/04-review.md)

## Where does my change belong?

| Kind of change | Goes in |
| --- | --- |
| A DV2.0 modeling rule, or a dbt/SQL formatting rule | `docs/standards/` |
| How our vault is layered | `docs/architecture/` |
| A modeling decision and its rationale | `docs/architecture/decisions/` |
| How we work a vault change through to release | `docs/process/` |
| The method an agent should follow to build a model | `skills/` |
| A DV2.0 term people keep asking about | `docs/glossary.md` |

## Style for the docs themselves

<!-- TODO: heading levels, sentence case, line length, how to phrase do/don't rules, whether a worked hub/link/satellite example is required. -->

## Changing a skill

<!-- TODO: how to test that a skill still produces conforming models after an edit. -->

## Review and approval

<!-- TODO: who must approve a modeling standard change vs. a process tweak, how many approvals. See CODEOWNERS. -->
