## Aleksandr Dolgopolov

Backend engineer, seven years in fintech and high-load systems. I build payment infrastructure and distributed backends where a race condition means lost money, not a failed test.

Currently working on a payment platform in the iGaming vertical.

### What I do

**Payments.** State machines, idempotency, multi-PSP routing, reconciliation, chargebacks, card issuing, KYC/KYB, P2P exchange.

**Crypto.** Production wallets on EOS, Ethereum, TRON, BSC and TON. Deposits and withdrawals, block watchers, HD wallets, escrow, swaps. Decimal arithmetic that doesn't silently lose money.

**Making things not fall over.** Distributed locks, transactional outbox, migrating large collections without downtime. Observability set up from scratch twice: Prometheus, Grafana, Loki, Tempo, OpenTelemetry.

**Leading.** Tech lead for a team of 5-10. Owned 8 domains and a shared internal library. Spent three years moving a monolith to modular hexagonal architecture, one domain at a time.

### Stack

`TypeScript` `Node.js` `NestJS` `Fastify`
`PostgreSQL` `MongoDB` `Redis` `ClickHouse`
`Kafka` `RabbitMQ` `BullMQ`
`Docker` `Kubernetes` `GitLab CI` `Prometheus` `Grafana` `OpenTelemetry`

### Open source

| Project | What it does |
|---|---|
| [promise-deduplicate](https://github.com/AleksDolgop/promise-deduplicate) | Collapses concurrent identical promises by key. A hundred callers, one actual call. Running in production |
| [tl-type](https://github.com/AleksDolgop/tl-type) | VS Code extension for Telegram Type Language schemas |
| [time-offset](https://github.com/AleksDolgop/time-offset) | Accumulative calculator for time offsets and intervals |

**Working on now:** an open server-side MTProto stack. Schema codegen, crypto primitives, transport, server.

Telegram published the protocol and the clients but never the server. I spent five years writing one behind closed doors. Now building an open implementation from scratch.

### Writing

I write about techniques from systems that handle real load, and about production incidents where the symptom has nothing to do with the cause.

🇷🇺 [Telegram](https://t.me/aleksdolgop_ru) · [Habr](https://habr.com/ru/users/AleksDolgop/)
🇬🇧 [Telegram](https://t.me/aleksdolgop_en) · [dev.to](https://dev.to/aleksdolgop)
🎥 [YouTube](https://youtube.com/@aleksdolgop)

📫 `me@aleksdolgop.dev` · [aleksdolgop.dev](https://aleksdolgop.dev)
