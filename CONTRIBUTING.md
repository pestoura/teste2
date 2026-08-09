# Contributing

## Delivery model

Work toward the next usable, demonstrable baseline using small vertical slices and bounded work in progress.

Routine progression is automatic when applicable gates are `GREEN`, `PASS`, `SUPPORTED` or `ACCEPTED`. A gate that did not execute is not green.

## Branches and pull requests

- keep branches short-lived;
- keep each PR bounded to one coherent delivery slice or integration boundary;
- do not use CI as a remote linter when the same deterministic check can run before push;
- fix deterministic failures from their root cause before retrying;
- do not merge stale-green changes without revalidation when shared surfaces have moved.

## Definition of Delivery

A change is delivered only when the applicable set is satisfied:

```text
IMPLEMENTED
+ TESTED
+ INTEGRATED
+ SECURITY VALIDATED
+ EVIDENCED
+ OPERABLE (when applicable)
= DELIVERED
```

Project-specific runtime/live/recovery gates remain authoritative even when common quality gates are provided centrally.

## Architecture decisions

Record material decisions under `docs/adr/`. Prefer explicit invariants and executable architecture fitness checks over prose-only rules where practical.
