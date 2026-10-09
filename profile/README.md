<p align="center">
  <a href="https://devlab.group/">
    <img src="./assets/devlab-banner.png" alt="DevLab — We turn product goals into reliable systems. Protocol and infrastructure engineering." width="100%">
  </a>
</p>

<p align="center">
  <a href="https://devlab.group/">Website</a> &nbsp;·&nbsp;
  <a href="https://devlab.group/work">Selected work</a> &nbsp;·&nbsp;
  <a href="#how-we-work">How we work</a> &nbsp;·&nbsp;
  <a href="mailto:dmitry@devlab.group">Start a conversation</a>
</p>

## Engineering with ownership

We are **DevLab**, an engineering team building protocols, financial infrastructure, and the systems around them. Since 2018, we have worked on **20+ projects**, taking responsibility for architecture, implementation, integrations, and production delivery.

We work with founders and product teams on new products, help recover existing systems, and own technical workstreams alongside in-house engineers.

## What we build

| Focus | Engineering scope |
| :--- | :--- |
| **Protocols & DeFi** | Smart contracts, liquidity mechanics, oracles, governance, and settlement. |
| **RWA & tokenization** | Asset issuance, permissioned transfers, supply controls, and redemption on EVM and Solana. |
| **Payments & stablecoins** | Payment flows, treasury operations, settlement infrastructure, and agent commerce. |
| **Smart accounts & wallets** | Session keys, delegated execution, recovery, permissions, and wallet integrations. |
| **Backend & infrastructure** | APIs, indexers, integrations, deployment, monitoring, and production operations. |
| **Security & tooling** | Contract and infrastructure reviews, remediation, MCP scanning, and verifiable audit trails. |

[Explore our services →](https://devlab.group/services)

## How we work

**Architecture first. Weekly working software. Clear release criteria.**

1. **Assess.** Define the product goal, constraints, and success criteria. For existing systems, inspect the codebase, infrastructure, and operational risks.
2. **Design.** Document system boundaries, interfaces, data flows, permissions, and failure modes. Agree on scope, milestones, and ownership.
3. **Build.** Deliver in one-week sprints. Every Monday, hand over a working build for testing while the next sprint begins. Record feedback and technical decisions.
4. **Verify.** Review the complete system: code, integrations, access controls, migrations, failure paths, and production readiness.
5. **Release.** Deploy with monitoring, rollback conditions, operational records, and documentation that matches the shipped system.

Start with a focused architecture engagement, a defined build, a project takeover, or an ongoing technical partnership.

[Read about our delivery process →](https://devlab.group/how-we-work)

## Architecture, in practice

### Agent Commerce Gateway

A self-hosted gateway that lets AI agents discover, call, and pay for an existing API. Funds go directly to the merchant; the gateway holds neither buyer nor merchant private keys.

Our **34-page architecture document** shows how requirements become an implementation and delivery plan:

- Functional requirements and architecture decisions.
- C4 views, component boundaries, and execution flows.
- Payment verification, replay protection, settlement, and receipts.
- Quality attributes, SLOs, and a STRIDE threat model.
- Deployment, recovery, release gates, and acceptance criteria.

**[Read the architecture PDF →](https://devlab.group/_next/static/media/agent-commerce-arch.BDjsaLfd.pdf)** &nbsp; [Explore the code →](https://github.com/devlab-group/agent-commerce)

The document covers the initial design and planned extensions. The repository tracks current implementation and protocol support.

## Open source & public engineering

Tools and platforms we build in-house. Each repository documents its setup, scope, and usage terms.

### Protocols & financial infrastructure

| Project | What it does |
| :--- | :--- |
| **[Agent Commerce Gateway](https://github.com/devlab-group/agent-commerce)** | Connects existing APIs to AI agents through HTTP and MCP, with x402 payments and a shared execution pipeline. Self-hosted and non-custodial. |
| **[RWA Platform · EVM](https://github.com/devlab-group/rwa-platform-evm)** | Permissioned ERC-20 tokenization with auditor-attested supply changes, controlled transfers, and on-chain cash redemption. |

### Security & operations

| Project | What it does |
| :--- | :--- |
| **[MCP Scanner](https://github.com/devlab-group/mcp-scanner)** | Scans MCP servers, source trees, and packages, reporting security findings and analysis coverage gaps. |
| **[Postflight](https://github.com/devlab-group/postflight)** | A single-file Bash audit for Linux server security and health, with suggested fixes and text, JSON, or Prometheus output. |
| **[Immutable Audit](https://github.com/devlab-group/immutable-audit)** | An eBPF proof of concept for tamper-evident process execution logs: hash-chained events, a remote collector, and independent verification. |

[Browse all repositories →](https://github.com/orgs/devlab-group/repositories)

### Beyond the repositories

- **[ERC-8409](https://ethereum-magicians.org/t/erc-8409-signed-service-payment-quotes/29577)** — a draft proposal for provider-signed EVM service payment quotes, separating commercial terms from payment authorization and settlement.
- **[RepoLore](https://chatgpt.com/plugins/plugin_asdk_app_6a898067d0b08191af8af6660eb1a9a5)** — our plugin for tracing public code history through commits, pull requests, issues, and regressions.

---

### Tell us what you are building

A product brief, an architecture question, or a codebase that needs a second look is enough to start.

**[dmitry@devlab.group](mailto:dmitry@devlab.group)** &nbsp;·&nbsp; [devlab.group](https://devlab.group/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/sergeevdms/)
