# apaleo (apaleo)

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

apaleo is an API-first cloud hotel property-management system (PMS) and platform. Every capability - reservations, bookings, blocks, inventory, rate plans, availability, and finance - is exposed through documented REST APIs secured with OAuth 2.0, published as OpenAPI, with webhooks for real-time events, enabling an open marketplace of integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apaleo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apaleo/refs/heads/main/apis.yml)

## Tags

- Hospitality
- PMS
- Property Management
- Hotels
- API-First

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### apaleo Booking API

End-to-end reservation lifecycle - create bookings and reservations, fetch offers, manage groups and blocks, and run reservation actions such as check-in, check-out, amend, assign-unit, and cancel.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Booking+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Booking+V1)
- **Base URL:** `https://api.apaleo.com/booking/v1`

#### Tags

- Bookings
- Reservations
- Blocks

#### Properties

- [Documentation](https://apaleo.dev/guides/api/overview.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Booking+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Inventory API

Manage the physical inventory of properties, units, unit groups, and unit attributes - including property rollout actions such as clone, archive, and set-live.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Inventory+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Inventory+V1)
- **Base URL:** `https://api.apaleo.com/inventory/v1`

#### Tags

- Inventory
- Properties
- Units

#### Properties

- [Documentation](https://apaleo.dev/guides/api/overview.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Inventory+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Rate Plan API

Set up and update rate plans, rates, services, companies, and cancellation / no-show policies in real time, plus corporate and promo code lookups.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Rate+Plan+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Rate+Plan+V1)
- **Base URL:** `https://api.apaleo.com/rateplan/v1`

#### Tags

- Rate Plans
- Rates
- Policies

#### Properties

- [Documentation](https://apaleo.dev/guides/business-cases/revenue-management/inventory-rates.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Rate+Plan+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Availability API

Query real-time availability for units, unit groups, services, and properties, and adjust per-unit-group availability.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Availability+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Availability+V1)
- **Base URL:** `https://api.apaleo.com/availability/v1`

#### Tags

- Availability
- ARI
- Units

#### Properties

- [Documentation](https://apaleo.dev/guides/business-cases/revenue-management/inventory-rates.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Availability+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Finance API

Folios, charges, payments, refunds, invoices, routings, and the chart of accounts - covering the full accounting and ledger surface of the platform.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Finance+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Finance+V1)
- **Base URL:** `https://api.apaleo.com/finance/v1`

#### Tags

- Finance
- Folios
- Invoices

#### Properties

- [Documentation](https://apaleo.dev/guides/api/overview.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Finance+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Settings API

Account- and property-level configuration - city tax, capture policies, market segments, languages, sub-accounts, features, and time-slice definitions.

- **Human URL:** [https://api.apaleo.com/swagger/index.html?urls.primaryName=Settings+V1](https://api.apaleo.com/swagger/index.html?urls.primaryName=Settings+V1)
- **Base URL:** `https://api.apaleo.com/settings/v1`

#### Tags

- Settings
- Configuration
- Tax

#### Properties

- [Documentation](https://apaleo.dev/guides/api/overview.html)
- [API Reference](https://api.apaleo.com/swagger/index.html?urls.primaryName=Settings+V1)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### apaleo Webhook API

Create and manage webhook subscriptions for real-time events across topics such as Reservation, Folio, Invoice, RatePlan, Block, Unit, and Property, with per-topic event filters and wildcards.

- **Human URL:** [https://webhook.apaleo.com/swagger/index.html](https://webhook.apaleo.com/swagger/index.html)
- **Base URL:** `https://webhook.apaleo.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://apaleo.dev/guides/api/overview.html)
- [API Reference](https://webhook.apaleo.com/swagger/index.html)
- [OpenAPI](openapi/apaleo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apaleo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apaleo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/apaleo)
- [LinkedIn](https://www.linkedin.com/company/apaleo)
- [Website](https://www.apaleo.com)
- [Documentation](https://apaleo.dev)
- [Plans](plans/apaleo-plans-pricing.yml)
- [Rate Limits](rate-limits/apaleo-rate-limits.yml)
- [Fin Ops](finops/apaleo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
