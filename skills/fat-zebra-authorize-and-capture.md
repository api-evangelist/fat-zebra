---
name: Authorize then capture
description: Place a card authorization and capture it later (delayed capture / auth-and-capture).
api: openapi/fat-zebra-gateway.json
operations: [create-an-authorization, capture-an-authorization, release-an-authorization]
---

# Authorize then capture (Fat Zebra Gateway)

Auth: HTTP Basic. Base URL `https://gateway.pmnts.io/v1.0`.

## Steps
1. `POST /purchases` as an authorization (`create-an-authorization`) with `amount`, unique `reference`, `currency`, card or `card_token`, and `capture: false`.
2. On approval (`response_code == "00"`) store the returned purchase `id`.
3. Capture funds with `POST /purchases/{id}/capture` (`capture-an-authorization`), optionally for a lesser amount.
4. To cancel instead, release the hold with `DELETE /purchases/{id}` (`release-an-authorization`).

## Rules
- Same `reference` idempotency as a purchase.
- A declined authorization surfaces via `response_code` (`errors/fat-zebra-decline-codes.yml`).
