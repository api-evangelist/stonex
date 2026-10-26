# StoneX (stonex)

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

StoneX Group is a global financial services organization that provides execution, risk management, market intelligence, and post-trade services across asset classes and markets to institutional, commercial, and retail clients. StoneX offers REST APIs for payments, clearing, and futures trading with OAuth 2.0 authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Finance
- Financial Services
- Payments
- Clearing
- Futures
- Trading
- Risk Management

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### StoneX Payments API

The StoneX Payments REST API enables cross-border payment processing in 140+ currencies with local currency acceptance and settlement. Uses Bearer token authentication over HTTPS with TLS 1.3. Available in sandbox and production environments.

- **Human URL:** [https://docs.payments.stonex.io/](https://docs.payments.stonex.io/)

#### Tags

- Payments
- Cross-Border Payments
- FX
- REST

#### Properties

- [Documentation](https://docs.payments.stonex.io/)
- [Getting Started](https://docs.payments.stonex.io/docs/quickstart-guide-1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stonex-clearing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-clearing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/stonex-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StoneX Clearing API

The StoneX Clearing REST API provides programmatic access to accounts, trading, and document management for clearing clients. Supports OAuth 2.0 authentication with JWT tokens. Available in UAT (api.clearing.uat.stonex.com) and production (api.clearing.stonex.com).

- **Human URL:** [https://docs.clearing.stonex.com/](https://docs.clearing.stonex.com/)

#### Tags

- Clearing
- Trading
- Accounts
- REST

#### Properties

- [Documentation](https://docs.clearing.stonex.com/docs)
- [Getting Started](https://docs.clearing.stonex.com/docs/getting-started/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-clearing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stonex-clearing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-clearing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/stonex-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StoneX GF Futures API

The StoneX GF (GAIN Futures) API provides institutional-grade access to futures trading including market data, order management, account and position tracking, margin calculations, contract lookup, and real-time price feeds for futures contracts.

- **Human URL:** [https://futures-media.stonex.com/gfapi/index.html](https://futures-media.stonex.com/gfapi/index.html)

#### Tags

- Futures
- Trading
- Market Data
- Institutional

#### Properties

- [Documentation](https://futures-media.stonex.com/gfapi/index.html)
- [Postman Collection](collections/stonex-clearing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-clearing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/stonex-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StoneX Developer Portal

The StoneX Developer Storefront provides access to all StoneX API products with subscription keys, documentation, and developer resources for integrating with StoneX financial services.

- **Human URL:** [https://developer.stonex.com/](https://developer.stonex.com/)

#### Tags

- Developer Portal
- API Management

#### Properties

- [Documentation](https://developer.stonex.com/documentation)
- [Products](https://developer.stonex.com/products)
- [Postman Collection](collections/stonex-clearing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-clearing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/stonex-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stonex-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/stonex)
- [LinkedIn](https://www.linkedin.com/company/stonex-group)
- [Website](https://www.stonex.com)
- [Developer  Portal](https://developer.stonex.com/)
- [Documentation](https://developer.stonex.com/documentation)
- [L L Ms Txt](https://developer.stonex.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
