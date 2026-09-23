![Crafting Express agent interface](docs/images/crafting-express-header.png)

# Crafting Express Edition

**Your Agents. Your Infra.**

Crafting Express is an interactive demo and playground that lets you evaluate
Crafting’s agent execution and orchestration platform on your own machine.
See how Crafting connects agents to k8s clusters, manages credentials and dependencies,
coordinates handoffs, and gives engineers and agents access to the same sandboxes
and infrastructure.

> Express is for evaluation only. Production deployments use Crafting Enterprise.

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
- Sign up and log in
- Create Docker volumes for persisted states and data
- Create a Docker container to run _Crafting Express Edition_
- Show you how to access _Crafting Express Edition_ via Web UI and CLI

For more details, check out our [documentation](https://docs.sandboxes.cloud).

## Built for teams of agents

Crafting brings agent coordination and execution environments together in one
platform. Express gives you a local evaluation of that platform; production
infrastructure integrations and enterprise controls are available through Crafting
Enterprise.

- **Give agents access to real data to test their work.** Connect agents to real
  services and dependencies in production-like environments so they can run
  tests, inspect failures, and iterate on a fix. Agents and engineers can validate
  changes in parallel using isolated slices of your application stack.
  [Closing the loop with Crafting](https://www.crafting.dev/post/announcing-crafting-for-agents).

- **Scope tools and access according to each agent's role.** Define the tools, dependencies,
  and access each agent needs. The Crafting platform combines sandbox access
  controls, network isolation, and managed credentials to constrain what agents
  can reach as they coordinate across systems.
  [How infrastructure-level control works](https://www.crafting.dev/blog/ai-control-plane-infrastructure-vs-governance).

- **Share workspaces when collaboration calls for it.** Give agents dedicated
  environments or let multiple agents work in an existing workspace. Engineers
  can work alongside agents using the same codebase and development tools.
  [See how Faire collaborates with agents](https://www.crafting.dev/post/faire-agentic-stack-case-study).

- **Choose models without replacing your harness.** Crafting's native harness
  supports OpenRouter, compatible self-hosted endpoints, AWS Bedrock, and Google
  Cloud Vertex AI. Centrally managed model configuration lets you evaluate new
  models while keeping your agent definitions and execution environments.
  [Model-agnostic agent teams](https://www.crafting.dev/post/model-agnostic-agent-teams).

- **Delegate work to specialist agents.** A lead agent can split a task among
  coding, testing, and security agents. Sub-agents run in parallel with separate
  conversation contexts, return results to the lead, and receive follow-up work
  as needed. [Build an agent team](https://docs.sandboxes.cloud/guides/developers/build-agent.html#agent-team).

## Hitting the limits of Express?

Upgrade to the Enterprise edition to manage and run agents at scale.

- **Connect to your internal k8s cluster**: agents execute against your real infrastructure,
  not a local dependency
- **Multi-cloud and multi-region** by default: automated failover, no vendor lock-in
- **Securely manage access to dependencies**: credential injection scoped per agent,
  admin-managed, never exposed
- **SOC 2 Type II certified**: independently audited for security and availability

We'll get you up and running in two weeks or less.

[Talk to us about Enterprise →](https://crafting.dev/contact)

> **DISCLAIMER** — Crafting Express Edition is for **trial and evaluation purposes only** and is provided as-is without warranty.
> It is not the Enterprise Edition. For production use, contact Crafting.
