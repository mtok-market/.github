# Seeding the market

Early markets need visible prices before they have deep liquidity.

For mtok.market, seeding means putting a small number of real offers on the board so buyers and agents can see a live spot market instead of an empty concept.

## Good seed offers

Good seed offers are:

- small enough to lose without drama
- real enough to exercise USDC settlement and relay delivery
- boring enough to debug
- clear about model, price, expiration, and capacity

## Bad seed offers

Bad seed offers are:

- oversized
- manually patched
- dependent on one fragile provider account
- priced to signal ambition instead of actual willingness to sell

## Goal

The goal is not to fake liquidity.

The goal is to make the market legible: a buyer can inspect prices, an agent can read the API, and a seller can see the minimum shape needed to join.

