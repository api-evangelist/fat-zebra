---
name: Tokenize a card and charge it
description: Store a card as a reusable token, then charge that token (card-on-file / recurring setup).
api: openapi/fat-zebra-gateway.json
operations: [tokenize-a-card, create-a-purchase-with-a-token-1, create-a-payment-plan]
---

# Tokenize a card and charge it (Fat Zebra Gateway)

Auth: HTTP Basic. Base URL `https://gateway.pmnts.io/v1.0`.

## Steps
1. `POST /credit_cards` (`tokenize-a-card`) with card details to get a reusable `token`/alias (PCI scope stays with Fat Zebra).
2. Charge it: `POST /purchases` with the `card_token` (`create-a-purchase-with-a-token-1`) and a unique `reference`.
3. For recurring, `POST /payment_plans` (`create-a-payment-plan`) referencing the customer/token to schedule ongoing charges.

## Rules
- Never store PANs yourself — Fat Zebra is PCI DSS certified (`conformance/fat-zebra-conformance.yml`); use tokens.
- Idempotency via `reference`; declines via `response_code`.
