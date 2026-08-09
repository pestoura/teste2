# Jarvas Project Template

This repository is the staging candidate for the universal Jarvas/JDS GitHub Template Repository.

Target repository identity:

```text
pestoura/jarvas-project-template
```

Canonical bootstrap source:

```text
pestoura/jarvas-engineering-platform
commit: 02b7336088b970644c3ce5c07591a9d128df936d
templates/fresh-repository/
```

## Intended use

After this repository is renamed to `jarvas-project-template` and marked as a GitHub **Template repository**, create new projects through **Use this template**.

Do not use the generic GitHub **New repository** flow when a new project is expected to start under JDS, because that flow creates an empty repository.

## Template boundary

This repository contains only project-neutral bootstrap material. Shared JDS implementation remains in `jarvas-engineering-platform` and product-specific code/gates belong to each created project.

Do not add a language, framework, container, cloud, browser, MCP, infrastructure or deployment assumption to this universal template. Repeated specialized patterns may later be offered as optional templates/presets without changing this baseline.
