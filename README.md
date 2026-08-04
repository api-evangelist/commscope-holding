# CommScope Holding (commscope-holding)

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

CommScope is a global provider of communications-network infrastructure, including fiber-optic and copper cabling, antenna systems, and cloud- managed enterprise networking. Following its acquisitions of ARRIS (2019) and the Ruckus Wi-Fi business, CommScope's primary public developer surface is the RUCKUS One API, a JSON REST surface for managing Wi-Fi networks, ICX switches, access points, venues, and managed-service-provider delegation. Companion product lines (RUCKUS Cloud, RUCKUS IoT, ICX RESTCONF, SmartZone, Cloudpath, Unleashed Multi- Site Manager, SmartCell Insight) ship their own REST/RESTCONF APIs and are documented through the CommScope and RUCKUS Networks developer centers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Access Points
- Cabling
- Connectivity
- ICX Switches
- Infrastructure
- Networking
- RUCKUS
- Wi-Fi

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-05-19

## APIs

### RUCKUS One API

JSON REST API for the RUCKUS One cloud-managed networking platform. Hosted on three regional bases (api.ruckus.cloud, api.eu.ruckus.cloud, api.asia.ruckus.cloud). Authentication is OAuth2 client credentials: a tenant generates an API key in the RUCKUS One UI and exchanges client_id/client_secret for a JSON Web Token bearer credential. Many write operations are asynchronous and return a requestId; the caller polls the activity service until SUCCESS. Supports venues, Wi-Fi networks (SSIDs), access points, ICX switches, connected clients, DPSK pools, resident portals, and MSP delegation.

- **Human URL:** [https://docs.ruckus.cloud/api](https://docs.ruckus.cloud/api)
- **Base URL:** `https://api.ruckus.cloud`

#### Tags

- Access Points
- Cloud Management
- ICX Switches
- Networking
- REST
- RUCKUS
- Wi-Fi

#### Properties

- [Documentation](https://docs.ruckus.cloud/api)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)
- [Postman Collection](https://github.com/commscope-ruckus/RUCKUS-One-Postman) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection Cloud](https://github.com/commscope-ruckus/RUCKUS-Cloud-Postman)
- [OpenAPI](openapi/ruckus-one-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ruckus-one-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ruckus-one-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RUCKUS SmartZone Public API

REST and OpenAPI surface for managing on-premises SmartZone controllers (SZ144, SZ300, vSZ-E, vSZ-H) and ICX Management. Used to integrate SmartZone with NMS, monitoring, and provisioning pipelines. Authentication and base URL are tenant-specific to the controller deployment.

- **Human URL:** [https://docs.commscope.com/](https://docs.commscope.com/)

#### Tags

- Controllers
- Networking
- REST
- RUCKUS
- SmartZone
- Wi-Fi

#### Properties

- [Documentation](https://docs.commscope.com/)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)
- [Postman Collection](collections/ruckus-one-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ruckus-one-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RUCKUS ICX RESTCONF API

RESTCONF API for ICX switches running FastIron 09.0.10/10.0.20 (GA). Models are YANG-based and follow standard RESTCONF semantics. Covers ICX 7150, 7250, 7450, 7550, 7650, 7850, 8200.

- **Human URL:** [https://www.ruckusnetworks.com/developer-central/](https://www.ruckusnetworks.com/developer-central/)

#### Tags

- ICX
- Networking
- RESTCONF
- RUCKUS
- Switches
- YANG

#### Properties

- [Documentation](https://www.ruckusnetworks.com/developer-central/)
- [Postman Collection](collections/ruckus-one-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ruckus-one-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RUCKUS IoT Platform API

REST API (v2.2) for the RUCKUS IoT Platform Controller. Manages the IoT controller, IoT-enabled access points, and downstream devices and sensors.

- **Human URL:** [https://www.ruckusnetworks.com/developer-central/](https://www.ruckusnetworks.com/developer-central/)

#### Tags

- Controllers
- IoT
- Networking
- REST
- RUCKUS

#### Properties

- [Documentation](https://www.ruckusnetworks.com/developer-central/)
- [Postman Collection](collections/ruckus-one-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ruckus-one-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/commscope)
- [Website](https://www.commscope.com/)
- [Ruckus Networks](https://www.ruckusnetworks.com/)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)
- [Product Documentation](https://docs.commscope.com/)
- [Ruckus Cloud Docs](https://docs.ruckus.cloud/)
- [Git Hub](https://github.com/commscope-ruckus)
- [Investors](https://ir.commscope.com/)
- [Privacy](https://www.commscope.com/privacy-statement/)
- [JSON-LD](json-ld/commscope-holding-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/ruckus-one-network-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/commscope-holding-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
