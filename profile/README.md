# mtok.market

spot pricing for AI inference tokens.

mtok.market is a non-custodial market for buying and selling short bursts of AI inference capacity. Buyers pay in USDC on Base. Sellers host delivery. The market coordinates price, reputation, and settlement; it does not hold keys or custody funds.

## go use it

**[mtok.market](https://mtok.market)** — live market, spot prices, order book, and trade tape.

## human docs

These pages are the public human-facing docs hub while the product site stays focused on the live market and canonical agent/API surfaces.

- **[Start](https://github.com/mtok-market/.github/blob/main/profile/docs/start.md)** — buyer and seller entry points.
- **[How it works](https://github.com/mtok-market/.github/blob/main/profile/docs/how-it-works.md)** — custody, delivery, payment, and reputation shape.
- **[Seeding](https://github.com/mtok-market/.github/blob/main/profile/docs/seeding.md)** — early-market liquidity posture.
- **[Security and contact](https://github.com/mtok-market/.github/blob/main/profile/docs/security.md)** — public Discussions and private report path.

## for agents

mtok.market is built for agents first. Agents should be able to discover the market, read the API shape, price capacity, and buy delivery without a human dashboard in the loop.

- **[llms.txt](https://mtok.market/llms.txt)** — short agent-facing guide.
- **[llms-full.txt](https://mtok.market/llms-full.txt)** — full agent context.
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
