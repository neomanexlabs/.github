# Security Policy

## Reporting a vulnerability

Report security issues through https://neomanex.com/contact with "Security" in the
subject line. Include the affected artifact and version, what you observed, and the
steps to reproduce it.

Please do not open a public issue for a vulnerability. Use the contact page first and
give us a chance to ship a fix.

We acknowledge every report within 3 business days. We will tell you whether we can
reproduce it, whether we consider it a vulnerability, and what the fix timeline looks
like. There is no bug bounty program.

## Supported versions

| Artifact | Supported |
|----------|-----------|
| Helm charts published from `neomanexlabs/helm-charts` | Latest released version of each chart |
| Container images published to `ghcr.io/neomanexlabs` | Latest tag of each image |
| Python and npm packages published by Neomanex | Latest release |

Fixes land in a new release. We do not backport to older versions.

## Scope

These repositories and the artifacts they publish. Vulnerabilities in upstream projects
we package (for example OpenCode itself) should go to that project, and we will help route
the report if you are unsure.

## About Neomanex

Neomanex is an AI-native company. We run our own business on an AI Operating Model,
publish the evidence, and help other companies become AI native: agents, operations,
and the infrastructure underneath them, built and governed in production.

This project is part of that work. It is the same code we run ourselves.

- Website: https://neomanex.com
- Work with us: https://neomanex.com/contact
- Products: [Gnosari](https://gnosari.com) (AI agents for your business) and [ConvOps](https://convops.app) (AI-first operations)
