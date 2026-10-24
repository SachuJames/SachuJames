<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:0e7490,100:22d3ee&height=200&section=header&text=Sachu%20James&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20FinTech&descAlignY=58&descAlign=50&descSize=18&descColor=99f6e4" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=750&lines=Backend+engineer+building+trading+infrastructure;Shipped%3A+matching+engines%2C+task+queues%2C+ledgers%2C+Solana+programs;Open-source+contributor" alt="Typing SVG" />
</div>

<br/>

---

## About

Backend engineer based in Kerala, India, working on trading infrastructure, distributed systems, and Web3. B.Tech in Computer Science at KTU (2023 to 2027). Previously a full stack developer at SpearHub (remote, Nov 2025 to Apr 2026).

Currently building **Meridian**, a memory-mapped columnar store for time-series data in Rust.

---

## Featured Work

**Trading and Market Infrastructure**

- **[tickforge](https://github.com/SachuJames/tickforge)** - Deterministic nanosecond-precision market microstructure simulator and matching engine (C++20), fully reproducible runs.
- **[limit-order-book](https://github.com/SachuJames/limit-order-book)** - Price-time priority matching engine in Rust: dense price levels, pooled orders, zero-allocation hot path.
- **[chainbook](https://github.com/SachuJames/chainbook)** - A limit order book that lives entirely on-chain (Solidity, Foundry): escrowed funds, price-time priority, partial fills.
- **[itch-feed](https://github.com/SachuJames/itch-feed)** - ITCH 5.0 market data feed handler in Rust: seeded UDP simulator, lock-free SPSC ring buffer, gap detection with retransmit requests.

**Distributed Systems and Backend**

- **[distributed-task-queue](https://github.com/SachuJames/distributed-task-queue)** - Redis Streams task queue with retries, idempotency, backpressure, dead-letter queues, and live observability.
- **[ledger-forge](https://github.com/SachuJames/ledger-forge)** - Double-entry accounting ledger (Go core, NestJS API) with idempotent posting and a live WebSocket feed.
- **[lightweight-api-gateway](https://github.com/SachuJames/lightweight-api-gateway)** - Programmable HTTP API gateway (Node.js, Fastify, Redis, PostgreSQL) with a React dashboard.
- **[skypod](https://github.com/SachuJames/skypod)** - A small Go service run like a platform: Helm chart with autoscaling, Terraform for EKS, Prometheus dashboards and alerts, ArgoCD.

**AI Agents and Tooling**

- **[agent-pay](https://github.com/SachuJames/agent-pay)** - Payment rails for AI agents: wallets, spending limits, human-in-the-loop approvals, double-entry ledger, on-chain settlement.
- **[mcp-gateway](https://github.com/SachuJames/mcp-gateway)** - Gateway for Model Context Protocol servers: auth, scopes, rate limiting, audit logging.
- **[agent-evals](https://github.com/SachuJames/agent-evals)** - Evaluation harness for AI agents: YAML task suites, tool-use loop, scorers, traces, regression tracking.

**More**

- **[solana-payment-streaming](https://github.com/SachuJames/solana-payment-streaming)** - Solana payment-streaming protocol: SPL tokens per second, cliffs, cancellations, TypeScript SDK.
- **[cloudtrim](https://github.com/SachuJames/cloudtrim)** - Kubernetes rightsizing CLI (Python, published on PyPI): compares requests against real usage and prices the waste.

---

## Tech Stack

<table align="center">
  <tr>
    <td align="center"><strong>Languages</strong></td>
    <td><img src="https://skillicons.dev/icons?i=python,go,rust,cpp,ts,js,java,solidity&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Backend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,nodejs,nestjs,express,spring&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Frontend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=react,html,css,tailwind&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Database & Cache</strong></td>
    <td><img src="https://skillicons.dev/icons?i=postgresql,redis&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>DevOps</strong></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,nginx,linux,git&theme=dark"/></td>
  </tr>
</table>

Working with Solana and Anchor, the XRP Ledger, Redis Streams, and Prometheus day to day.

---

## Open Source

Contributions to Python, Rust, and Web3 libraries. One fix has shipped so far; the rest are open, and the rotki one is deep in maintainer review.

**Shipped:** [massive-com/client-python](https://github.com/massive-com/client-python/pull/1040) - my TLS configuration fix (PR #1034) was folded in by the maintainer and released in v2.9.0, with a co-author credit.

Open:

- [rotki/rotki#13282](https://github.com/rotki/rotki/pull/13282) - Save bitcoin tx checkpoints per address (five rounds of review feedback addressed)
- [Lumiwealth/lumibot#1182](https://github.com/Lumiwealth/lumibot/pull/1182) - Fix stale daily fills after loading minute data
- [alpacahq/alpaca-py#792](https://github.com/alpacahq/alpaca-py/pull/792) - Add CashInterest model to CreateAccountRequest
- [strawberry-graphql/strawberry#4644](https://github.com/strawberry-graphql/strawberry/pull/4644) - Allow passing a dict as the config argument of Schema
- [XRPLF/xrpl-py#1058](https://github.com/XRPLF/xrpl-py/pull/1058) - Fail closed on unknown transaction flag names
- [XRPLF/xrpl-py#1064](https://github.com/XRPLF/xrpl-py/pull/1064) - Add a debug option to submit_and_wait
- [ApeWorX/web3.py#3891](https://github.com/ApeWorX/web3.py/pull/3891) - Fix AsyncHTTPProvider deadlock on cancelled session-lock acquire
- [ApeWorX/eth-abi#274](https://github.com/ApeWorX/eth-abi/pull/274) - Make encoding errors subclass ValueError and TypeError

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-SachuJames-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SachuJames)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sachu%20James-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sachu-li)
[![Portfolio](https://img.shields.io/badge/Portfolio-sachu--james.vercel.app-14b8a6?style=for-the-badge&logo=vercel&logoColor=white)](https://sachu-james.vercel.app/)

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:0e7490,100:0a0a0f&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>
