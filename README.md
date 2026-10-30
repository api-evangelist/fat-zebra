# Fat Zebra

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fat Zebra is an Australian payments company (founded 2012, Sydney) providing a card-present and card-not-present payment gateway and processing platform for merchants, ISOs, and software platforms across Australia and New Zealand. Its API-first Gateway handles Visa, Mastercard, and Amex purchases, authorizations and captures, refunds and voids, card tokenization, 3D Secure, recurring payment plans, direct debits and direct credits over local bank rails, chargeback handling, batch processing, and hosted payment pages (PayNow), alongside wallet acceptance for Apple Pay, Google Pay, and Click to Pay. A separate Partner API lets platforms and ISOs create and board their own sub-merchants onto acquirer connections programmatically. The developer surface is a genuine, well-documented ReadMe hub at docs.fatzebra.com with four downloadable OpenAPI definitions, and the runtime platform is branded pmnts (gateway.pmnts.io). Authentication is HTTP Basic using a username and API token.

**Areas:** Payments · Australia · Payment Gateway · Payment Processing · Acquiring · Card Payments · Tokenization · Recurring Billing · Direct Debit · Hosted Payment Pages · Merchant Onboarding

## Fat Zebra on APIs.io

Everything profiled for Fat Zebra is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fat-zebra/](https://apis.io/providers/fat-zebra/)** — or go straight to one of the APIs or properties below.

### APIs (31)

- [Fat Zebra Acquirer connections API](https://apis.io/apis/fat-zebra/fat-zebra-acquirer-connections-api/) — A merchant's connections to acquirers — board, list, update, enable/disable.
- [Fat Zebra Acquirers API](https://apis.io/apis/fat-zebra/fat-zebra-acquirers-api/) — The acquirer catalogue this partner may board onto.
- [Fat Zebra Applicable Surcharge API](https://apis.io/apis/fat-zebra/fat-zebra-applicable-surcharge-api/) — The Applicable Surcharge API from Fat Zebra — 1 operation(s) for applicable surcharge.
- [Fat Zebra Authenticate API](https://apis.io/apis/fat-zebra/fat-zebra-authenticate-api/) — The Authenticate API from Fat Zebra — 3 operation(s) for authenticate.
- [Fat Zebra Bank Accounts API](https://apis.io/apis/fat-zebra/fat-zebra-bank-accounts-api/) — The Bank Accounts API from Fat Zebra — 2 operation(s) for bank accounts.
- [Fat Zebra Batches API](https://apis.io/apis/fat-zebra/fat-zebra-batches-api/) — The Batches API from Fat Zebra — 4 operation(s) for batches.
- [Fat Zebra Chargebacks API](https://apis.io/apis/fat-zebra/fat-zebra-chargebacks-api/) — The Chargebacks API from Fat Zebra — 4 operation(s) for chargebacks.
- [Fat Zebra Credit Cards API](https://apis.io/apis/fat-zebra/fat-zebra-credit-cards-api/) — The Credit Cards API from Fat Zebra — 3 operation(s) for credit cards.
- [Fat Zebra Customers API](https://apis.io/apis/fat-zebra/fat-zebra-customers-api/) — The Customers API from Fat Zebra — 3 operation(s) for customers.
- [Fat Zebra Direct Credits API](https://apis.io/apis/fat-zebra/fat-zebra-direct-credits-api/) — The Direct Credits API from Fat Zebra — 3 operation(s) for direct credits.
- [Fat Zebra Direct Debits API](https://apis.io/apis/fat-zebra/fat-zebra-direct-debits-api/) — The Direct Debits API from Fat Zebra — 3 operation(s) for direct debits.
- [Fat Zebra Disputes API](https://apis.io/apis/fat-zebra/fat-zebra-disputes-api/) — The Disputes API from Fat Zebra — 1 operation(s) for disputes.
- [Fat Zebra Fat Zebra Billing API](https://apis.io/apis/fat-zebra/fat-zebra-fat-zebra-billing-api/) — The Fat Zebra Billing API from Fat Zebra — 1 operation(s) for fat zebra billing.
- [Fat Zebra Health API](https://apis.io/apis/fat-zebra/fat-zebra-health-api/) — The Health API from Fat Zebra — 2 operation(s) for health.
- [Fat Zebra Invoice Imports API](https://apis.io/apis/fat-zebra/fat-zebra-invoice-imports-api/) — The Invoice Imports API from Fat Zebra — 1 operation(s) for invoice imports.
- [Fat Zebra Invoices API](https://apis.io/apis/fat-zebra/fat-zebra-invoices-api/) — The Invoices API from Fat Zebra — 2 operation(s) for invoices.
- [Fat Zebra Merchants API](https://apis.io/apis/fat-zebra/fat-zebra-merchants-api/) — The Merchants API from Fat Zebra — 7 operation(s) for merchants.
- [Fat Zebra Oauth Clients API](https://apis.io/apis/fat-zebra/fat-zebra-oauth-clients-api/) — The Oauth Clients API from Fat Zebra — 1 operation(s) for oauth clients.
- [Fat Zebra Partner API](https://apis.io/apis/fat-zebra/fat-zebra-partner-api/) — The authenticated partner (self).
- [Fat Zebra Payment Plans API](https://apis.io/apis/fat-zebra/fat-zebra-payment-plans-api/) — The Payment Plans API from Fat Zebra — 2 operation(s) for payment plans.
- [Fat Zebra Purchases API](https://apis.io/apis/fat-zebra/fat-zebra-purchases-api/) — The Purchases API from Fat Zebra — 11 operation(s) for purchases.
- [Fat Zebra Refunds API](https://apis.io/apis/fat-zebra/fat-zebra-refunds-api/) — The Refunds API from Fat Zebra — 3 operation(s) for refunds.
- [Fat Zebra Reports API](https://apis.io/apis/fat-zebra/fat-zebra-reports-api/) — The Reports API from Fat Zebra — 2 operation(s) for reports.
- [Fat Zebra Settlement API](https://apis.io/apis/fat-zebra/fat-zebra-settlement-api/) — The Settlement API from Fat Zebra — 1 operation(s) for settlement.
- [Fat Zebra SSO API](https://apis.io/apis/fat-zebra/fat-zebra-sso-api/) — Partner SSO enforcement — read state, enforce, disable.
- [Fat Zebra Transactions API](https://apis.io/apis/fat-zebra/fat-zebra-transactions-api/) — The Transactions API from Fat Zebra — 2 operation(s) for transactions.
- [Fat Zebra Users API](https://apis.io/apis/fat-zebra/fat-zebra-users-api/) — Partner dashboard users — CRUD plus deactivate/reactivate.
- [Fat Zebra Utilities API](https://apis.io/apis/fat-zebra/fat-zebra-utilities-api/) — The Utilities API from Fat Zebra — 3 operation(s) for utilities.
- [Fat Zebra Utlities API](https://apis.io/apis/fat-zebra/fat-zebra-utlities-api/) — The Utlities API from Fat Zebra — 1 operation(s) for utlities.
- [Fat Zebra Pay Pal API](https://apis.io/apis/fat-zebra/fat-zebra-pay-pal-api/) — The Pay Pal API from Fat Zebra — 15 operation(s) for pay pal.
- [Fat Zebra Webhooks API](https://apis.io/apis/fat-zebra/fat-zebra-webhooks-api/) — The Webhooks API from Fat Zebra — 2 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Fat Zebra Webhooks](https://apis.io/asyncapis/fat-zebra/fat-zebra-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [fat-zebra](https://apis.io/servers/fat-zebra/fat-zebra/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fat Zebra Agentic Access](https://apis.io/agentic-access/fat-zebra/fat-zebra-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Fat Zebra Billing](https://apis.io/collections/fat-zebra/open-fat-zebra-billing/)
- [FDMS TPP Merchant Onboarding](https://apis.io/collections/fat-zebra/open-fat-zebra-fdms-tpp-merchant-onboarding/)
- [gateway](https://apis.io/collections/fat-zebra/open-fat-zebra-gateway/)
- [Fat Zebra Partner API](https://apis.io/collections/fat-zebra/open-fat-zebra-partner/)

#### Overlays (4)

OpenAPI overlays, including conversational phrasing for each operation.

- [Fat Zebra Billing Overlay](https://apis.io/overlays/fat-zebra/fat-zebra-billing-overlay/)
- [Fat Zebra Fdms Tpp Merchant Onboarding Overlay](https://apis.io/overlays/fat-zebra/fat-zebra-fdms-tpp-merchant-onboarding-overlay/)
- [Fat Zebra Gateway Overlay](https://apis.io/overlays/fat-zebra/fat-zebra-gateway-overlay/)
- [Fat Zebra Partner Overlay](https://apis.io/overlays/fat-zebra/fat-zebra-partner-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Fat Zebra Authentication](https://apis.io/security/fat-zebra/fat-zebra-authentication/)
- [Fat Zebra Domain Security](https://apis.io/security/fat-zebra/fat-zebra-domain-security/)
- [Fat Zebra Trust Center](https://apis.io/security/fat-zebra/fat-zebra-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.fatzebra.com/)
- [Documentation](https://docs.fatzebra.com/docs/introduction)
- [Getting started](https://docs.fatzebra.com/docs/getting-started)
- [API reference](https://docs.fatzebra.com/reference/purchases)
- [Pricing](https://www.fatzebra.com/platform/pricing)
- [Sign up](https://www.fatzebra.com/contact/sales)
- [Support](https://www.fatzebra.com/contact/support)
- [Changelog](https://docs.fatzebra.com/changelog/welcome-to-pmnts)
- [Blog](https://www.fatzebra.com/company/news)
- [Security](https://www.fatzebra.com/security)
- [Compliance](https://docs.fatzebra.com/docs/pci-certification)
- [Privacy policy](https://www.fatzebra.com/privacy-policy)
- [GitHub](https://github.com/fatzebra)
- [Status](https://status.fatzebra.com/)

## API Evangelist rating

**Kin Score 52.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 60.3 |
| Contract governance | 18.2 |
| Operational transparency | 43.4 |
| Developer ergonomics | 54.2 |
| Access clarity | 46.1 |

**Agent readiness 36.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 33.5** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fat-zebra/](https://apis.io/providers/fat-zebra/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Fat Zebra: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fat-zebra/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
