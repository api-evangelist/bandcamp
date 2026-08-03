# Bandcamp (bandcamp)

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

Bandcamp is an artist-direct music marketplace and streaming platform. Its developer APIs are limited and gated to labels and merchandise fulfillment partners; access is granted on request and uses OAuth 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bandcamp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bandcamp/refs/heads/main/apis.yml)

## Tags

- Music
- Marketplace
- Indie
- Audio
- Sales
- Merch

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Bandcamp Account API

Account API for retrieving the list of bands a user manages and basic account metadata. OAuth 2.0 client credentials with token endpoint at /oauth_token; access tokens expire after one hour.

- **Human URL:** [https://bandcamp.com/developer](https://bandcamp.com/developer)
- **Base URL:** `https://bandcamp.com/api`

#### Tags

- Account
- Bands

#### Properties

- [Documentation](https://bandcamp.com/developer)
- [Postman Collection](collections/bandcamp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandcamp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bandcamp Sales Report API

Sales Report API for labels: retrieves sales line items (digital, physical, merch, subscriptions) over a date range. Restricted to labels.

- **Human URL:** [https://bandcamp.com/developer/sales](https://bandcamp.com/developer/sales)
- **Base URL:** `https://bandcamp.com/api`

#### Tags

- Sales
- Reporting
- Labels

#### Properties

- [Documentation](https://bandcamp.com/developer/sales)
- [Postman Collection](collections/bandcamp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandcamp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bandcamp Merch Orders API

Merch Orders API for fulfillment partners: list and update merchandise orders (mark shipped, set tracking). Restricted to merchandise fulfillment partners.

- **Human URL:** [https://bandcamp.com/developer/merch](https://bandcamp.com/developer/merch)
- **Base URL:** `https://bandcamp.com/api`

#### Tags

- Merch
- Orders
- Fulfillment

#### Properties

- [Documentation](https://bandcamp.com/developer/merch)
- [Postman Collection](collections/bandcamp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandcamp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bandcamp)
- [Website](https://bandcamp.com/)
- [Developer Portal](https://bandcamp.com/developer)
- [Plans](plans/bandcamp-plans-pricing.yml)
- [Rate Limits](rate-limits/bandcamp-rate-limits.yml)
- [Fin Ops](finops/bandcamp-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
