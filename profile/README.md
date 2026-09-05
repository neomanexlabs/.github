# Neomanex Labs

Neomanex is an AI-native company. We run our own business on an AI Operating Model,
publish the evidence, and help other companies become AI native: agents, operations,
and the infrastructure underneath them, built and governed in production.

This organization holds the code we open source. It is the same code we run ourselves.

## What we publish

### [helm-charts](https://github.com/neomanexlabs/helm-charts)

Helm chart for OpenCode: one AI coding agent server per repository on Kubernetes, with
persistent workspaces, git identity and RBAC as values. Install from the OCI registry:

```bash
helm install opencode oci://ghcr.io/neomanexlabs/charts/opencode --version 1.4.3
```

Or from the chart repository index:

```bash
helm repo add neomanexlabs https://neomanexlabs.github.io/helm-charts
```


### [regrun](https://github.com/daviunx/regrun)

YAML-driven regression runner for APIs, MCP servers, SQL, bash and WebSocket in one
suite. You describe the checks in YAML, it runs them in order and reports what broke.

```bash
pip install regrun
```

Currently at https://github.com/daviunx/regrun. Transfer into this organization is pending.

## Why we open source this

We run every one of these artifacts in our own production, so what you install is what
we depend on, not a demo carved out for publishing. Authority comes from evidence: the
fastest way to show how we build and govern AI systems is to hand over the tools we use
to do it. And the point of the company is to help other companies become AI native, which
starts with the infrastructure being reachable by anyone.

## Work with us

Tell us what you are trying to automate and we will tell you whether it is ready:
https://neomanex.com/contact

Issues on these repositories are the support channel. Security reports get a first
response within 3 business days; everything else is best effort.

## About Neomanex

Neomanex is an AI-native company. We run our own business on an AI Operating Model,
publish the evidence, and help other companies become AI native: agents, operations,
and the infrastructure underneath them, built and governed in production.

This project is part of that work. It is the same code we run ourselves.

- Website: https://neomanex.com
- Work with us: https://neomanex.com/contact
- Products: [Gnosari](https://gnosari.com) (conversational data collection: AI agents that turn conversations into structured data) and [ConvOps](https://convops.app) (AI-first operations)
