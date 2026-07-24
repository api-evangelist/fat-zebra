---
name: Accept a card payment
description: Take a one-off card purchase through the Fat Zebra Gateway, including a 3DS/SCA check, and confirm the result.
api: openapi/fat-zebra-gateway.json
operations: [create-a-purchase-with-fraud-screening-1, fetch-a-purchase]
---

# Accept a card payment (Fat Zebra Gateway)

Auth: HTTP Basic — your gateway `username` + API `token`. Base URL `https://gateway.pmnts.io/v1.0` (sandbox `https://gateway.pmnts-sandbox.io/v1.0`).

## Steps
1. (Optional, recommended) Run a 3DS/SCA check client-side with `fatzebra.js` `verifyCard`; capture the `fz.sca.success` payload for liability shift.
2. `POST /purchases` (`create-a-purchase-with-fraud-screening-1`) with `amount` (cents), a unique `reference`, `currency`, `customer_ip`, and either raw card fields (`card_number`, `card_holder`, `card_expiry`, `cvv`) or a `card_token`. Include the 3DS result when you have one.
3. Read the response envelope: `successful: true` and `response.response_code == "00"` means approved. Any other `response_code` is a decline — see `errors/fat-zebra-decline-codes.yml` and mask fraud/lost-stolen reasons as a generic decline to the buyer.
4. `GET /purchases/{id}` (`fetch-a-purchase`) to re-read status.

## Rules
- Idempotency: the `reference` is the idempotency key — re-submitting the same reference returns the existing purchase, not a duplicate (`conventions/fat-zebra-conventions.yml`).
- Errors: envelope is `{ successful, errors[], response }`; `422` carries field-validation messages.
- Test cards: `sandbox/fat-zebra-sandbox.yml`.
