# Security Policy

## Engineering security baseline

This project inherits the applicable JDS engineering/security controls selected from its `.jarvas/engineering.yml` manifest.

Security requirements are risk- and capability-driven. A project-specific control may strengthen the central baseline but must not silently weaken a mandatory JDS control.

## Secrets

Do not commit credentials, tokens, private keys, cookies, browser storage/session material or production secrets.

Use the approved secret/identity mechanism for the project. Secret values must not be copied into issue text, pull-request descriptions, logs, screenshots or retained evidence.

## Reporting

Do not open a public issue containing exploitable security details or secret material. Use an appropriate private disclosure path for the repository owner and rotate any exposed credential immediately.

## Delivery

A security-sensitive change is not delivered merely because code exists or unit tests pass. Applicable security, acceptance, evidence and rollback/recovery gates remain part of the project's Definition of Delivery.
