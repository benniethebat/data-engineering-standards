# Documentation Map

Where the Data Vault 2.0 practice is written down, and what belongs in each place. The tree is split by domain, not by audience — the same documents serve human contributors and AI agents.

## The four domains

| Domain | Path | Answers | Nature |
| --- | --- | --- | --- |
| Standards | [standards/](standards/) | What are the DV2.0 and dbt rules? | Reference — **source of truth** |
| Architecture | [architecture/](architecture/) | How is our vault layered, and why? | Explanation |
| Process | [process/](process/) | How do I take a vault change from idea to production? | How-to |
| Glossary | [glossary.md](glossary.md) | What do we mean by this DV2.0 term? | Reference |

Skills in [../skills/](../skills/) are the fifth piece: the method, packaged for an agent. They apply the standards and never redefine them.

## Rules of the tree

- **Standards are the source of truth.** They are written as do/don't rules.
- **Process docs and skills reference standards, they do not duplicate them.** A process doc says "apply [standards/data-vault-modeling.md](standards/data-vault-modeling.md)"; it never restates the rule.
- **Architecture explains, standards prescribe.** If you find yourself writing "must" in an architecture doc, it belongs in standards.
- **Modeling decisions get an ADR.** Use [architecture/decisions/0001-template.md](architecture/decisions/0001-template.md).

## Lifecycle

The process docs run in order across the lifecycle of a vault change:

1. [process/01-planning.md](process/01-planning.md)
2. [process/02-design.md](process/02-design.md)
3. [process/03-implementation.md](process/03-implementation.md)
4. [process/04-review.md](process/04-review.md)
5. [process/05-release.md](process/05-release.md)

## Contents

- `standards/data-vault-modeling.md` — hubs, links, satellites, business keys, hashing, load metadata
- `standards/dbt-style.md` — SQL and dbt code formatting conventions
- `standards/testing.md` — tests a vault model must carry
- `standards/security.md` — sensitive data in vault structures, secrets, access
- `architecture/overview.md` — the layers of our vault and how data moves through them
- `architecture/decisions/` — ADRs, numbered sequentially from `0001-template.md`
- `glossary.md` — DV2.0 vocabulary as we use it
