# 05 — Release

Getting a merged vault change into production: promoting the models, running the initial load or backfill, confirming the vault is intact, and communicating the change. This document describes the procedure only; the checks that must pass are defined in [../standards/testing.md](../standards/testing.md).

## Entry criteria

<!-- TODO: what must come out of [04-review.md](04-review.md). -->

## Steps

<!-- TODO: fill in each step. -->

1. Promote to production — TODO mechanism and cadence
2. Initial load / backfill of new vault structures — TODO ordering (hubs before links before satellites), and how history is loaded
3. Run post-deployment checks — per [../standards/testing.md](../standards/testing.md)
4. Confirm downstream marts still build — TODO
5. Cut the release notes — move Unreleased entries in [../../CHANGELOG.md](../../CHANGELOG.md) into a version
6. Announce — TODO where, and to whom

## Verification

<!-- TODO: how we confirm the load did what it was supposed to — row counts, key integrity, no unexpected satellite churn. -->

## Rollback

<!-- TODO: how to reverse a release against an insert-only vault, and who decides. -->

## Exit criteria

<!-- TODO: what "done" means, and where the work is closed out. -->
