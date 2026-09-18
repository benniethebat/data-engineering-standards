# Testing Standard

The tests a Data Vault model must carry before it can ship: what is required on hubs, links, and satellites, what runs in CI, and what a failure means. This document is the source of truth for test requirements — process docs and skills link here rather than restating them.

Rules are written as do/don't pairs.

## Minimum required tests by vault object

<!-- TODO: the non-negotiable set for each. -->

| Object | Required tests |
| --- | --- |
| Staging | TODO |
| Hub | TODO |
| Link | TODO |
| Satellite | TODO |

- Do: TODO
- Don't: TODO

## Test types

<!-- TODO: generic tests, singular tests, unit tests, source freshness — when each applies to vault objects. -->

- Do: TODO
- Don't: TODO

## Vault-specific integrity checks

<!-- TODO: hash key uniqueness, orphan link keys, satellite parent references, no duplicate hash diffs, insert-only violations. -->

- Do: TODO
- Don't: TODO

## Severity and thresholds

<!-- TODO: warn vs error, acceptable failure thresholds, who gets paged. -->

- Do: TODO
- Don't: TODO

## CI

<!-- TODO: what runs on a PR vs on merge vs on schedule, and what blocks a merge. -->

- Do: TODO
- Don't: TODO

## Handling failures

<!-- TODO: triage, waivers, and how a waiver is recorded. -->
