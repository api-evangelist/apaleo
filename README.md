# apaleo (apaleo)

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
