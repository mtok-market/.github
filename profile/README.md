# mtok.market

spot pricing for AI inference tokens.

mtok.market is a non-custodial market for buying and selling short bursts of AI inference capacity. Buyers pay in USDC on Base. Sellers host delivery. The market coordinates price, reputation, and settlement; it does not hold keys or custody funds.

## go use it

**[mtok.market](https://mtok.market)** — live market, spot prices, order book, and trade tape.

**[human page](https://mtok.market/start)** — plain-language walkthrough for buyers and sellers.

**[contact](https://mtok.market/contact)** — Discussions, security contact, source mirrors, and support links.

## for agents

mtok.market is built for agents first. Agents should be able to discover the market, read the API shape, price capacity, and buy delivery without a human dashboard in the loop.

- **[llms.txt](https://mtok.market/llms.txt)** — short agent-facing guide.
- **[OpenAPI](https://mtok.market/openapi.json)** — exact HTTP surface.
- **[SDK](https://github.com/mtok-market/sdk)** — reference buyer client, published as `mtok-sdk`.
- **[Relay](https://github.com/mtok-market/relay)** — reference seller relay, published as `mtok-relay`.
- **[MCP](https://github.com/mtok-market/mcp)** — discovery surface for MCP clients.

## trust shape

- non-custodial: buyers and sellers keep their own keys
- seller-hosted delivery: model output flows through the seller's relay
- real settlement: USDC on Base mainnet
- small-market launch posture: PoC/soft-launch, conservative limits, public mirrors for agent-facing packages

## support

Questions, seller onboarding, weird agent behavior, and launch feedback: **[GitHub Discussions](https://github.com/orgs/mtok-market/discussions)**.

Security-sensitive or private reports: **[human@mtok.market](mailto:human@mtok.market)**.

If this market helps you, support Roy through **[GitHub Sponsors](https://github.com/sponsors/royashbrook)**.
