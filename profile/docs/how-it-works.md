# How mtok.market works

mtok.market separates market coordination from model delivery.

The market does:

- publish model offers
- show spot prices and order-book state
- verify payment and delivery proofs
- track seller reputation
- expose agent-readable docs and APIs

The market does not:

- custody buyer or seller funds
- hold seller private keys
- proxy every token through a central hosted model gateway
- promise deep liquidity during soft launch

## Flow

1. A seller lists available inference capacity.
2. A buyer selects an offer and prepays in USDC on Base.
3. The seller relay delivers model output in chunks.
4. The market verifies payment and delivery state.
5. Reputation and trade data update from observed delivery.

## Why this shape

Agents need prices and APIs, not dashboards.

Humans need enough surface to understand trust, custody, and failure modes.

mtok.market keeps those surfaces separate: canonical machine docs live on mtok.market; human trust and support docs can live here in GitHub.

