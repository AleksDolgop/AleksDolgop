## Aleksandr Dolgopolov

Backend engineer with 7+ years in fintech and high-load systems.
I build payment infrastructure, crypto integrations and distributed backends that handle money correctly under concurrency.

**Currently:** payment platform in the iGaming vertical.

---

### What I work on

**High-load backends.** Systems processing financial operations under concurrent load — where a race condition means real money lost, not a failed test.

**Payment infrastructure.** Payment state machines, idempotency, multi-PSP routing, reconciliation, chargebacks, card issuing, KYC/KYB flows, P2P exchange.

**Crypto integrations.** Production wallets across EOS, Ethereum, TRON, BSC and TON: deposits and withdrawals, block watchers, HD wallets, escrow contracts, swaps, precise decimal arithmetic.

**Reliability.** Distributed locks, transactional outbox, idempotent migrations of large collections without downtime, observability from scratch — Prometheus, Grafana, Loki, Tempo, OpenTelemetry.

**Team.** Tech lead for a team of 5–10. Owner of 8 domains and a shared internal library. Migrated a monolith to a modular hexagonal architecture over three years.

---

### Stack

`TypeScript` `Node.js` `NestJS` `Fastify`
`PostgreSQL` `MongoDB` `Redis` `ClickHouse`
`Kafka` `RabbitMQ` `BullMQ`
`Docker` `Kubernetes` `GitLab CI` `Prometheus` `Grafana` `OpenTelemetry`

---

### Open source

| Project | What it does |
|---|---|
| [promise-deduplicate](https://github.com/AleksDolgop/promise-deduplicate) | Deduplicates concurrent identical promises by key — one in-flight call instead of a hundred. Used in production |
| [tl-type](https://github.com/AleksDolgop/tl-type) | VS Code extension for Telegram Type Language schemas |
| [time-offset](https://github.com/AleksDolgop/time-offset) | Accumulative calculator for time offsets and intervals |

**Building now:** an open server-side MTProto stack — schema-first codegen, crypto primitives, transport and server.
Telegram published the protocol and the clients, but not the server. I spent five years writing one; now I'm building an open implementation from scratch.

---

### Writing

I write about incidents from production — the kind where the symptom has nothing to do with the cause.

- 🇷🇺 [Telegram](https://t.me/aleksdolgop_ru) · [Habr](https://habr.com/)
- 🇬🇧 [Telegram](https://t.me/aleksdolgop_en) · [dev.to](https://dev.to/)

---

📫 `me@aleksdolgop.dev` · [aleksdolgop.dev](https://aleksdolgop.dev)
