# Fat Zebra (fat-zebra)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fat Zebra is an Australian payments company (founded 2012, Sydney) providing a card payment gateway and processing platform for merchants, ISOs, and software platforms across Australia and New Zealand. Its API-first Gateway handles Visa, Mastercard, and Amex purchases, authorizations and captures, refunds and voids, card tokenization, 3D Secure, recurring payment plans, direct debits and direct credits over local bank rails, chargeback handling, batch processing, and hosted payment pages (PayNow), plus wallet acceptance for Apple Pay, Google Pay, and Click to Pay. A separate Partner API lets platforms and ISOs create and board their own sub-merchants. The runtime platform is branded pmnts (gateway.pmnts.io).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fat-zebra/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fat-zebra/refs/heads/main/apis.yml)

**Developer portal:** [https://docs.fatzebra.com/](https://docs.fatzebra.com/)

**Home market:** Australia

## Tags

- Payments
- Australia
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Tokenization
- Recurring Billing
- Direct Debit
- Hosted Payment Pages
- Merchant Onboarding

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Fat Zebra Gateway API

The core payments Gateway — 98 documented operations across 73 paths covering purchases, authorizations and captures, refunds and voids, card tokenization, customers and bank accounts, direct debits and direct credits, chargebacks, batches, recurring payment plans, surcharging, and webhook management. OpenAPI 3.1. Auth is HTTP Basic (username + API token).

- **Human URL:** [https://docs.fatzebra.com/reference/purchases](https://docs.fatzebra.com/reference/purchases)
- **Base URL:** `https://gateway.pmnts.io/v1.0`

#### Properties

- [OpenAPI](openapi/fat-zebra-gateway.json)
- [Documentation](https://docs.fatzebra.com/docs/purchases-overview)
- [API Reference](https://docs.fatzebra.com/reference/purchases)

### Fat Zebra Partner API

The Partner (v2) API for ISOs and software platforms to programmatically create and manage their own sub-merchants and acquirer connections — 30 operations across 22 paths covering partner self/identity, merchant create/board/lifecycle, credential rotation, acquirer connection management, SSO enforcement, and dashboard users. OpenAPI 3.1. Auth is HTTP Basic.

- **Human URL:** [https://docs.fatzebra.com/docs/introduction](https://docs.fatzebra.com/docs/introduction)
- **Base URL:** `https://gateway.pmnts.io/v2/partners`

#### Properties

- [OpenAPI](openapi/fat-zebra-partner.json)
- [Documentation](https://docs.fatzebra.com/docs/introduction)
- [API Reference](https://docs.fatzebra.com/reference/showself)

### Fat Zebra Billing API

An early usage-based Billing API (OpenAPI 3.0.3) exposing billing entities and a batch usage-record push for metered billing. Documented server is the sandbox host `billing.pmnts-sandbox.io`. Auth is HTTP Basic.

- **Human URL:** [https://docs.fatzebra.com/](https://docs.fatzebra.com/)
- **Base URL:** `https://billing.pmnts-sandbox.io/api/v1/`

#### Properties

- [OpenAPI](openapi/fat-zebra-billing.json)
- [Documentation](https://docs.fatzebra.com/)

### Fat Zebra FDMS TPP Merchant Onboarding API

A Third-Party Processor (TPP) merchant onboarding API for the FDMS acquiring integration (OpenAPI 3.0.3) — create and list merchants and an internal onboard operation. Documented server is the sandbox host `acquiring-sandbox.fatzebra.com.au`. Auth is HTTP Basic.

- **Human URL:** [https://docs.fatzebra.com/](https://docs.fatzebra.com/)
- **Base URL:** `https://acquiring-sandbox.fatzebra.com.au/api/v1`

#### Properties

- [OpenAPI](openapi/fat-zebra-fdms-tpp-merchant-onboarding.json)
- [Documentation](https://docs.fatzebra.com/)

## Common Properties

- [Website](https://www.fatzebra.com/)
- [Developer Portal](https://docs.fatzebra.com/)
- [Documentation](https://docs.fatzebra.com/docs/introduction)
- [API Reference](https://docs.fatzebra.com/reference/purchases)
- [Getting Started](https://docs.fatzebra.com/docs/getting-started)
- [Change Log](https://docs.fatzebra.com/changelog/welcome-to-pmnts)
- [GitHub Organization](https://github.com/fatzebra)
- [Status Page](https://status.fatzebra.com/)
- [Pricing](https://www.fatzebra.com/platform/pricing)
- [Blog](https://www.fatzebra.com/company/news)
- [Support](https://www.fatzebra.com/contact/support)
- [Security](https://www.fatzebra.com/security)
- [Privacy Policy](https://www.fatzebra.com/privacy-policy)
- [Integrations](https://www.fatzebra.com/platform/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
