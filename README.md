# Semsee (semsee)

Semsee is a digital small-commercial insurance quoting platform built on the SEMCI (Single Entry, Multiple Company Interface) principle, connecting independent agents to 50+ carriers and MGAs across multiple lines of business via API and RPA integrations. The platform handles submissions, multi-carrier quoting, proposals, and binding. Semsee exposes a partner Upload/Download (AMS) integration capability and SSO rather than a public, self-serve developer API. Semsee was acquired by iBynd in March 2026.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/semsee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/semsee/refs/heads/main/apis.yml)

## Tags

- Insurance
- Insurtech
- Commercial Insurance
- Quoting
- Submissions

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Semsee Submissions API

Partner-gated Upload/Download integration that pushes ACORD-based application and submission data from an agency management system (AMS) into the Semsee platform for multi-carrier quoting. No public, self-serve developer reference, endpoints, or base URL are documented; integration requires Semsee development resources and a partner agreement.

- **Human URL:** [https://semsee.com/partners](https://semsee.com/partners)

#### Tags

- Submissions
- Applications
- ACORD

#### Properties

- [Documentation](https://semsee.com/partners)
- [OpenAPI](openapi/semsee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/semsee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/semsee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Semsee Quotes API

Partner-gated download of multi-carrier quote results back into an AMS or commercial rater so agents can compare and bind without re-keying. No public endpoint, schema, or base URL is published; access is via partner integration only.

- **Human URL:** [https://semsee.com/partners](https://semsee.com/partners)

#### Tags

- Quotes
- Rating
- Download

#### Properties

- [Documentation](https://semsee.com/partners)
- [OpenAPI](openapi/semsee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/semsee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/semsee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Semsee Carriers API

Carrier and MGA connectivity through which Semsee routes submissions to 50+ markets via carrier API and RPA integrations, including class-code and market-appetite matching. This is internal platform connectivity; no public developer-facing carrier API is documented.

- **Human URL:** [https://semsee.com/carriers-mgas-semsee](https://semsee.com/carriers-mgas-semsee)

#### Tags

- Carriers
- MGA
- Appetite

#### Properties

- [Documentation](https://semsee.com/carriers-mgas-semsee)
- [OpenAPI](openapi/semsee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/semsee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/semsee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Semsee Webhooks API

No public webhook or event-notification surface is documented by Semsee. This entry is a placeholder reflecting that event-driven callbacks, if they exist, are part of a private partner integration and are not publicly specified.

- **Human URL:** [https://semsee.com/partners](https://semsee.com/partners)

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://semsee.com/partners)
- [OpenAPI](openapi/semsee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/semsee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/semsee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/semsee)
- [Website](https://www.semsee.com)
- [Documentation](https://help.semsee.com)
- [Plans](plans/semsee-plans-pricing.yml)
- [Rate Limits](rate-limits/semsee-rate-limits.yml)
- [Fin Ops](finops/semsee-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
