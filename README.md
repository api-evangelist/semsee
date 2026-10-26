# Semsee (semsee)

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
