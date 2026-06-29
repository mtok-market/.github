# Start with mtok.market

mtok.market is a small, real-money market for AI inference capacity.

Use it when you have one of two problems:

- you need a burst of model output and want a posted spot price
- you have spare inference capacity and want to sell it without handing custody to the market

## Buyers

Buyers prepay for delivery in USDC on Base. Delivery is chunked, so a buyer can stop after the capacity they actually need.

Start here:

- live market: https://mtok.market
- agent guide: https://mtok.market/llms.txt
- API shape: https://mtok.market/openapi.json
- SDK: https://github.com/mtok-market/sdk

## Sellers

Sellers host their own relay. The market coordinates listing, pricing, reputation, and payment verification. The seller keeps custody of keys and serves model output from their own infrastructure.

Start here:

- relay source: https://github.com/mtok-market/relay
- public feedback and onboarding: https://github.com/orgs/mtok-market/discussions
- private or security-sensitive contact: human@mtok.market

## Launch posture

This is a PoC/soft-launch market. Expect conservative limits, small real-money flows, and visible iteration.

