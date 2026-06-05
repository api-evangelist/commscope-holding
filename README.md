# CommScope Holding (commscope-holding)

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
