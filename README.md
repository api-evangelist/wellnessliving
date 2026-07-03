# WellnessLiving (wellnessliving)

WellnessLiving is all-in-one business-management software for fitness studios, gyms, spas, salons, and wellness businesses - scheduling, point of sale, memberships/passes, marketing, and client engagement in one platform, serving over 10 million users worldwide. WellnessLiving publishes a real, extensive RESTful API (324+ JSON-over-HTTPS endpoints across 45+ resource areas as of the 2026-06-20 build) that powers its own Achieve client app and Elevate staff app - documented in an official public OpenAPI specification (github.com/wellnessliving/openapi) and public PHP/JavaScript SDKs (wl-sdk, wl-sdk-js) - but the API itself is partner-gated: access requires contacting a WellnessLiving Account Executive or Support, completing an API Access Questionnaire, and signing an NDA and API Agreement before the Integrations Team issues application credentials for staging and production. Core resources cover clients/members, classes and schedules, one-on-one appointments, the shared booking/checkout wizard, memberships and passes (Purchase Options), staff, locations, business configuration, retail sales/catalog, payments (the Thoth payment microservice), authentication, rewards/loyalty, reviews, reporting, and a channel-based real-time WebSocket notification layer.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wellnessliving/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wellnessliving/refs/heads/main/apis.yml)

## Tags

- Fitness
- Wellness
- Spa
- Business Management
- Scheduling
- Memberships
- Point of Sale

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### WellnessLiving Clients API

Client (member) profile management, purchase history, and family relationships - the customer record at the center of every booking, membership, and sale.

- **Human URL:** [https://help.wellnessliving.com/en/articles/10697645-getting-started-with-the-wellnessliving-api](https://help.wellnessliving.com/en/articles/10697645-getting-started-with-the-wellnessliving-api)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Clients
- Members
- Profile
- Family

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://help.wellnessliving.com/en/articles/10697645-getting-started-with-the-wellnessliving-api)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Classes & Schedules API

Group class and event catalog plus the live schedule of bookable sessions - listing, viewing, filtering by location/staff/time, and cancelling a client's booked session.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Classes
- Schedules
- Group Fitness

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Appointments API

One-on-one appointment booking - service and staff availability, calendar day availability, and completing (or rescheduling) an appointment booking for one or more clients.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Appointments
- 1:1 Services

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Booking Wizard API

The multi-step booking/checkout engine shared by classes, events, and appointments - resolves the ordered wizard steps, prices and books the selected Purchase Option or payment method, and checks whether an existing booking can be cancelled.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Booking
- Checkout

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Memberships & Passes API

Purchase Options - memberships, class packages, and passes - plus the guest passes clients can extend to friends and family from an active membership.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Promotions
- Memberships
- Guest Pass

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Staff API

Staff directory, staff profile detail, create/update of a staff record, and the privilege set that governs what a signed-in staff member can access.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Staff

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Locations API

Business location directory and detail, plus creating/editing a location and its weekly working-hours schedule.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Locations

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Business API

Business-level profile and configuration - locale, franchise status, enabled services, subscription/plan state - and self-service creation of a new business account.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Business

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Sales & Catalog API

Retail storefront catalog (products, promotions, events, coupons), live cart pricing, checkout/payment for store items, and purchase receipts.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Catalog
- Purchases
- Point of Sale

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Payments API

The Thoth payment microservice underlying WellnessLiving checkout - client payment accounts, saved bank cards, manually charging/crediting an account, and daily transaction reporting.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Payments
- Thoth WlPay

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Authentication API

Session sign-in/sign-out and JWT token issuance for the officially published API, plus looking up a user's public login information within a business.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/getting-started/authentication-guide/](https://www.wellnessliving.com/developer-portal/getting-started/authentication-guide/)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Authentication
- Login

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/getting-started/authentication-guide/)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Rewards & Loyalty API

The WellnessLiving Rewards points program - current score and leaderboard rank, redeemable prizes, and the reward-earning actions configured for a business.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Rewards
- Loyalty

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Reviews API

Client reviews for a business location - submitting a rating and review, listing reviews, and posting a business reply.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Reviews

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Reports API

Business-intelligence reporting - single-report data, multi-report page collections, and an access check for a given report.

- **Human URL:** [https://www.wellnessliving.com/developer-portal/endpoints/endpoints](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- Reports

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://www.wellnessliving.com/developer-portal/endpoints/endpoints)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellnessLiving Real-Time Notifications API

The channel-based WebSocket push layer used by WellnessLiving's own web and mobile clients for live updates (report progress, visit status, messenger chat) - a client authorizes onto a channel with this REST call immediately after opening the socket.

- **Human URL:** [https://github.com/wellnessliving/openapi](https://github.com/wellnessliving/openapi)
- **Base URL:** `https://us.wellnessliving.com`

#### Tags

- WebSocket
- Real-Time

#### Properties

- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [API Reference](https://github.com/wellnessliving/openapi)
- [OpenAPI](openapi/wellnessliving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellnessliving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellnessliving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/wellnessliving-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/wellnessliving)
- [LinkedIn](https://www.linkedin.com/company/wellnesslivingsoftware)
- [Website](https://www.wellnessliving.com/)
- [Documentation](https://www.wellnessliving.com/developer-portal/getting-started/introduction/)
- [Plans](plans/wellnessliving-plans-pricing.yml)
- [Rate Limits](rate-limits/wellnessliving-rate-limits.yml)
- [Fin Ops](finops/wellnessliving-finops.yml)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
