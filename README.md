# Project

This repository is a neutral Jarvas/JDS project bootstrap.

It intentionally starts without assumptions about programming language, framework, runtime, cloud, browser automation, MCP, infrastructure or deployment model.

## Engineering baseline

The repository consumes `pestoura/jarvas-engineering-platform` and starts with only:

- JDS planning;
- mandatory repository secret scanning;
- delivery evidence;
- project-neutral collaboration/documentation scaffolding.

When the first real vertical slice is defined, enable auto-detection and/or add only the engineering capabilities that the project actually needs in `.jarvas/engineering.yml`.

## Delivery rule

```text
DISCOVER / DEFINE NEXT USABLE BASELINE
        -> IMPLEMENT SMALL VERTICAL SLICE
        -> RUN APPLICABLE FAST/SECURITY GATES
        -> INTEGRATE
        -> RUN APPLICABLE EXPENSIVE/LIVE GATES
        -> EVIDENCE
        -> DELIVER
```

Project-specific gates remain local until a central equivalent has proven parity.

## Template use

This repository is intended to become `pestoura/jarvas-project-template` and be marked as a GitHub **Template repository**. New projects should then be created with **Use this template**, not with the generic empty-repository flow.
