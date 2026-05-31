### Hey 👋

I'm building [Made on Sol](https://madeonsol.com) — a Solana trading intelligence platform and ecosystem directory.

**What MadeOnSol does:**

- 🔍 1,070 Solana tools tracked across 30 categories
- 📡 1,069 KOL wallets monitored in real-time across 11 DEX programs
- 🚀 23,000+ Pump.fun deployers scored by bonding rate
- 🧠 1M+ alpha wallets scored from 1.77M KOL trade records
- 💰 Self-calculated token prices and market caps from our own gRPC streams — zero third-party price APIs
- 📊 REST API, WebSocket streams, webhooks, MCP server, and x402 micropayments

**Tech stack:**

- Next.js, Tailwind CSS, self-hosted Supabase (PostgreSQL)
- Dual gRPC streams (Frankfurt + New York) via Yellowstone/Kaldera — <3s trade latency
- Dedicated Hetzner server — Xeon E-2176G, 64GB ECC RAM, NVMe RAID1, SATA RAID1 backup
- 180-day KOL trade retention, 120-day wallet tracker retention
- All data sourced on-chain. No Birdeye, no DexScreener, no third-party price feeds.

**Open source packages:**

- [madeonsol](https://www.npmjs.com/package/madeonsol) — TypeScript SDK
- [madeonsol-x402](https://pypi.org/project/madeonsol-x402/) — Python SDK
- [mcp-server-madeonsol](https://www.npmjs.com/package/mcp-server-madeonsol) — MCP Server for AI agents
- [@madeonsol/plugin-madeonsol](https://www.npmjs.com/package/@madeonsol/plugin-madeonsol) — ElizaOS plugin
- [solana-agent-kit-plugin-madeonsol](https://www.npmjs.com/package/solana-agent-kit-plugin-madeonsol) — Solana Agent Kit plugin
- [madeonsol-x402](https://www.npmjs.com/package/madeonsol-x402) — x402 integration

**Stats:**

- 133 registered developers
- 500,000+ API requests served
- 174,000+ unique tokens tracked
- 370+ blog posts published
- $2,299 MRR — solo developer, $0 marketing spend

🔗 [madeonsol.com](https://madeonsol.com) · [API Docs](https://madeonsol.com/api-docs) · [Developer Portal](https://madeonsol.com/developer) · [Telegram Bot](https://t.me/MadeOnSolAlphaBot)
