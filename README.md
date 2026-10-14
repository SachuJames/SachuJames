# Sachu James

Backend engineer based in Kerala, India. B.Tech in Computer Science at KTU (2023 to 2027).

I build trading infrastructure and distributed systems: matching engines, task queues, double-entry ledgers, API gateways, and Solana programs. Before this I worked as a full stack developer at SpearHub (remote, Nov 2025 to Apr 2026).

Right now I am building a limit order book and matching engine in Rust.

## Projects

**[tickforge](https://github.com/SachuJames/tickforge)** - Market microstructure simulator in C++20. Deterministic event replay with nanosecond timestamps: order book, matching, and market data generation for testing trading logic.

**[distributed-task-queue](https://github.com/SachuJames/distributed-task-queue)** - Task queue on Redis Streams. Retries with backoff, idempotent enqueue, backpressure, dead-letter queues, Prometheus metrics, and a live dashboard.

**[ledger-forge](https://github.com/SachuJames/ledger-forge)** - Double-entry accounting ledger. A Go core owns the money math (balanced journals, idempotent posting, materialized balances) and a NestJS gateway owns auth and the API.

**[lightweight-api-gateway](https://github.com/SachuJames/lightweight-api-gateway)** - HTTP API gateway in Node.js and Fastify: routing, Redis rate limiting, circuit breakers, JWT auth, config hot reload, and a React admin UI.

**[solana-payment-streaming](https://github.com/SachuJames/solana-payment-streaming)** - SolStream: stream SPL tokens per second on Solana, with cliffs, cancellation, a TypeScript SDK, and a dashboard.

**[agent-pay](https://github.com/SachuJames/agent-pay)** - Payment rails for AI agents: per-agent wallets, spending limits, human approval for large transfers, a double-entry ledger, and Solana settlement.

## Open source

Open pull requests in Python fintech and Web3 libraries. None merged yet; the rotki one is deep in maintainer review.

- [rotki/rotki#13282](https://github.com/rotki/rotki/pull/13282) - bitcoin tx checkpoints per address (five rounds of review feedback addressed)
- [Lumiwealth/lumibot#1182](https://github.com/Lumiwealth/lumibot/pull/1182) - fix stale daily fills after loading minute data
- [alpacahq/alpaca-py#792](https://github.com/alpacahq/alpaca-py/pull/792) - add the CashInterest model to account requests
- [massive-com/client-python#1034](https://github.com/massive-com/client-python/pull/1034) - honor SSL_CERT_FILE and REQUESTS_CA_BUNDLE for TLS config
- [strawberry-graphql/strawberry#4644](https://github.com/strawberry-graphql/strawberry/pull/4644) - allow a dict as the Schema config argument
- [XRPLF/xrpl-py#1058](https://github.com/XRPLF/xrpl-py/pull/1058) - fail closed on unknown transaction flag names
- [ApeWorX/web3.py#3891](https://github.com/ApeWorX/web3.py/pull/3891) - fix an AsyncHTTPProvider deadlock on a cancelled lock acquire
- [ApeWorX/eth-abi#274](https://github.com/ApeWorX/eth-abi/pull/274) - make encoding errors subclass ValueError and TypeError

## Stack

Python, Go, Rust, TypeScript, Java, C++. FastAPI, Node.js, NestJS, Spring Boot. Postgres, Redis, Docker. Solana (Anchor), web3.py, xrpl-py.

## Links

[Portfolio](https://sachu-james.vercel.app/) · [LinkedIn](https://linkedin.com/in/sachu-li) · sachujames15543@gmail.com
