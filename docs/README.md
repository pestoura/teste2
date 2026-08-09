# Documentation guide

This directory is intentionally a **skeleton**. A repository created from the Jarvas Project Template should replace placeholder guidance with evidence-backed product documentation as implementation begins.

## Minimum documentation set for a real project

| Document | Purpose |
|---|---|
| Product overview / main `README.md` | What the product is, current state, capabilities, non-capabilities and quick start. |
| `docs/architecture/` | Current and target architecture, trust boundaries and important runtime flows. |
| `docs/adr/` | Decisions that materially constrain design, security or operations. |
| `SECURITY.md` | Security boundary, vulnerability reporting and operational security assumptions. |
| `CONTRIBUTING.md` | How changes are proposed, validated and accepted. |

## Recommended status vocabulary

Documentation should make these states visibly different:

- **IMPLEMENTED** — corresponding code/configuration exists;
- **TESTED** — executable evidence exists;
- **DEPLOYED** — deployment evidence exists;
- **SUPPORTED_LIVE** — live acceptance exists for the stated scope;
- **PLANNED** — roadmap/design only;
- **BLOCKED** — a named dependency prevents progress;
- **NOT_SUPPORTED** — explicitly outside the current product boundary.

Avoid turning a roadmap item into a current capability merely because it is documented.

## Diagram guidance

Use Mermaid when it materially clarifies the project. Useful views normally include:

1. system context;
2. component/container view;
3. trust/security boundaries;
4. an important request or lifecycle sequence;
5. current vs target state when the project is migrating.

See [`architecture/README.md`](architecture/README.md) for a starter pattern.

## Relationship with JDS

JDS can validate documentation quality and select applicable engineering gates, but it cannot determine product truth by itself. The repository remains responsible for keeping documentation aligned with executable and live evidence.
