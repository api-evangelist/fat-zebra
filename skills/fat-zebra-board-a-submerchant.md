---
name: Board a sub-merchant (Partner API)
description: As a partner/ISO, create a sub-merchant and board it onto an acquirer connection programmatically.
api: openapi/fat-zebra-partner.json
operations: [createMerchant, boardAcquirer, activateMerchant, listMerchants]
---

# Board a sub-merchant (Fat Zebra Partner API)

Auth: HTTP Basic — partner `username` + API `token`. Base URL `https://gateway.pmnts.io/v2/partners` (sandbox `https://gateway.pmnts-sandbox.io/v2/partners`).

## Steps
1. `POST /merchants` (`createMerchant`) to create the sub-merchant record.
2. `POST /merchants/{username}/acquirers` (`boardAcquirer`) to board the merchant onto an acquirer connection (supply `acquirer`, optional `currencies`).
3. `POST` activate (`activateMerchant`) once boarding succeeds.
4. `GET /merchants` (`listMerchants`) to confirm state.

## Rules
- Boarding is idempotent per acquirer: re-posting the same acquirer returns the existing connection instead of duplicating (`conventions/fat-zebra-conventions.yml`).
- On `422 fields`, correct the named input and re-POST — the corrected retry is safe.
- `422 processor_error` means the request is fine but the upstream processor failed; retry.
