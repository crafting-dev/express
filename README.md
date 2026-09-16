# Crafting Express Edition

**Try the enterprise AI control plane in a single container.**

Crafting is the enterprise-ready AI control plane for multi-agent systems.
Secure, networked execution environments with built-in orchestration and network
isolation, built for teams that need agents to operate safely and reliably at scale.

**Crafting Express Edition** is a single-container evaluation build so you can
experience multi-agent orchestration firsthand. Spin up agents, coordinate
hand-offs, and see what it looks like when agents execute in isolated environments
with scoped credentials and real dependencies.


> ⚠️ **Express Edition is for trial and evaluation only.** It runs inside a
> single Docker container and is not suitable for production workloads. For
> enterprise-scale deployment — multi-cloud, multi-region, k8s integration, and
> SOC 2 Type II compliance — [contact us](https://crafting.dev).

## Quick Start

Download the Crafting CLI:

```sh
curl -sSL https://sandboxes.cloud/sh/install-cli | bash
```

Alternatively, you can download it [directly here](docs/Download.md).

Launch _Crafting Express Edition_ using a single command:

```sh
cs express start
```

It will guide you to:
- Sign-up and log in
- Create Docker volumes for persisted states and data
- Create a Docker container to run _Crafting Express Edition_
- Instructions on how to access _Crafting Express Edition_ via Web UI and CLI

For more details, check out our [documentation](https://docs.sandboxes.cloud).

## Hitting the limits of Express?

Upgrade to the Enterprise edition to manage and run agents at scale.

- **Connect to your k8s cluster** — agents execute against your real infrastructure,
  not a container
- **Multi-cloud and multi-region** by default — automated failover, no vendor lock-in
- **Secure access to internal systems** — credential injection scoped per agent,
  admin-managed, never exposed
- **SOC 2 Type II certified** — independently audited for security and availability

We'll get you up and running in two weeks or less.

[Talk to us about Enterprise →](https://crafting.dev/contact)

> **DISCLAIMER** — Crafting Express Edition runs inside a single Docker container
> for **trial and evaluation purposes only** and is provided as-is without warranty.
> It is not the Enterprise Edition. For production use, contact Crafting.
