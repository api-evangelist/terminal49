# Terminal49 (terminal49)

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

Terminal49 is an automated container and ocean-freight tracking platform. Its v2 REST API (JSON:API) lets shippers, forwarders, and logistics software track Bills of Lading, bookings, and container numbers across global ocean carriers and North American rail, returning normalized milestones, ETAs, terminal availability, holds, demurrage fees, and last free day, with webhooks for real-time updates.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/terminal49/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/terminal49/refs/heads/main/apis.yml)

## Tags

- Container Tracking
- Ocean Freight
- Supply Chain
- Logistics
- Shipping

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Terminal49 Tracking Requests API

Submit a Bill of Lading, booking, or container number plus carrier SCAC to ask Terminal49 to begin tracking a shipment, then list, retrieve, and edit those tracking requests.

- **Human URL:** [https://terminal49.com/docs/api-docs/api-reference/introduction](https://terminal49.com/docs/api-docs/api-reference/introduction)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Tracking Requests
- Bill of Lading
- Booking

#### Properties

- [Documentation](https://terminal49.com/docs/api-docs/getting-started/tracking-shipments-and-containers/)
- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terminal49 Shipments API

List and retrieve shipments with normalized BOL data, port of lading and discharge, vessel and voyage, POD ETA/ATA and destination ETA, and stop or resume tracking controls.

- **Human URL:** [https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/](https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Shipments
- ETA
- Milestones

#### Properties

- [Documentation](https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/)
- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terminal49 Containers API

List, retrieve, and refresh containers with equipment type, current status, terminal availability, holds, demurrage fees, last free day, pickup appointment, rail milestones, and GeoJSON map data.

- **Human URL:** [https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/](https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Containers
- Availability
- Demurrage

#### Properties

- [Documentation](https://terminal49.com/docs/api-docs/getting-started/list-shipments-and-containers/)
- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terminal49 Transport Events API

Retrieve the timeline of normalized transport events (milestones such as vessel departed, vessel arrived, discharged, full out, and rail events) for a container.

- **Human URL:** [https://terminal49.com/docs/api-docs/api-reference/introduction](https://terminal49.com/docs/api-docs/api-reference/introduction)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Transport Events
- Milestones
- Webhooks

#### Properties

- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terminal49 Terminals & Shipping Lines API

Look up supported shipping lines and their SCAC codes, and retrieve terminal reference details at destination ports.

- **Human URL:** [https://terminal49.com/docs/api-docs/api-reference/introduction](https://terminal49.com/docs/api-docs/api-reference/introduction)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Terminals
- Shipping Lines
- SCAC

#### Properties

- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Terminal49 Webhooks API

Register, list, retrieve, edit, delete, and test webhooks (callback URLs Terminal49 POSTs to on updates), and review the webhook notifications and example payloads that have been sent.

- **Human URL:** [https://terminal49.com/docs/api-docs/in-depth-guides/quickstart/](https://terminal49.com/docs/api-docs/in-depth-guides/quickstart/)
- **Base URL:** `https://api.terminal49.com/v2`

#### Tags

- Webhooks
- Notifications
- Real-time

#### Properties

- [Documentation](https://terminal49.com/docs/api-docs/in-depth-guides/quickstart/)
- [API Reference](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [OpenAPI](openapi/terminal49-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terminal49.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terminal49.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Terminal49)
- [LinkedIn](https://www.linkedin.com/company/terminal49)
- [Website](https://www.terminal49.com)
- [Documentation](https://terminal49.com/docs/api-docs/api-reference/introduction)
- [Plans](plans/terminal49-plans-pricing.yml)
- [Rate Limits](rate-limits/terminal49-rate-limits.yml)
- [Fin Ops](finops/terminal49-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
