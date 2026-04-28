# CommScope Holding (commscope-holding)

CommScope is a global provider of communications-network infrastructure, including fiber-optic and copper cabling, antenna systems, and cloud-managed enterprise networking. Following its acquisitions of ARRIS (2019) and the Ruckus Wi-Fi business, CommScope's primary public developer surface is the RUCKUS One API, a JSON REST surface for managing Wi-Fi networks, ICX switches, access points, venues, and managed-service-provider delegation. Companion product lines (RUCKUS Cloud, RUCKUS IoT, ICX RESTCONF, SmartZone, Cloudpath, Unleashed Multi-Site Manager, SmartCell Insight) ship their own REST/RESTCONF APIs and are documented through the CommScope and RUCKUS Networks developer centers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

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
- **Modified:** 2026-04-26

## APIs

### RUCKUS One API
JSON REST API for the RUCKUS One cloud-managed networking platform. Hosted on regional bases (NA, EU, Asia). OAuth2 client-credentials authentication issues JWT bearer tokens; many write operations are asynchronous (HTTP 202 + activity polling). Supports venues, Wi-Fi networks (SSIDs), access points, ICX switches, connected clients, DPSK pools, resident portals, and MSP delegation.

**Base URL:** `https://api.ruckus.cloud`

**Human URL:** [https://docs.ruckus.cloud/api](https://docs.ruckus.cloud/api)

#### Tags

- Access Points, Cloud Management, ICX Switches, Networking, REST, RUCKUS, Wi-Fi

#### Properties

- [Documentation](https://docs.ruckus.cloud/api)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)
- [RUCKUS One Postman Collection](https://github.com/commscope-ruckus/RUCKUS-One-Postman)
- [RUCKUS Cloud Postman Collection](https://github.com/commscope-ruckus/RUCKUS-Cloud-Postman)
- [OpenAPI](openapi/ruckus-one-api-openapi.yml)

### RUCKUS SmartZone Public API
REST and OpenAPI surface for managing on-premises SmartZone controllers (SZ144, SZ300, vSZ-E, vSZ-H) and ICX Management.

**Human URL:** [https://docs.commscope.com/](https://docs.commscope.com/)

#### Tags

- Controllers, Networking, REST, RUCKUS, SmartZone, Wi-Fi

#### Properties

- [Documentation](https://docs.commscope.com/)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)

### RUCKUS ICX RESTCONF API
RESTCONF API for ICX switches (FastIron 09.0.10 and 10.0.20 GA). YANG-modeled, covers ICX 7150 through 8200 platforms.

**Human URL:** [https://www.ruckusnetworks.com/developer-central/](https://www.ruckusnetworks.com/developer-central/)

#### Tags

- ICX, Networking, RESTCONF, RUCKUS, Switches, YANG

### RUCKUS IoT Platform API
REST API (v2.2) for the RUCKUS IoT Platform Controller, managing IoT controllers, IoT-enabled APs, and downstream devices/sensors.

**Human URL:** [https://www.ruckusnetworks.com/developer-central/](https://www.ruckusnetworks.com/developer-central/)

#### Tags

- Controllers, IoT, Networking, REST, RUCKUS

## Common Properties

- [Website](https://www.commscope.com/)
- [RUCKUS Networks](https://www.ruckusnetworks.com/)
- [Developer Central](https://www.ruckusnetworks.com/developer-central/)
- [Product Documentation](https://docs.commscope.com/)
- [RUCKUS Cloud Docs](https://docs.ruckus.cloud/)
- [GitHub Org](https://github.com/commscope-ruckus)
- [Investors](https://ir.commscope.com/)
- [Privacy Statement](https://www.commscope.com/privacy-statement/)
- [JSON-LD Context](json-ld/commscope-holding-context.jsonld)
- [Network JSON Schema](json-schema/ruckus-one-network-schema.json)
- [Spectral Ruleset](rules/commscope-holding-rules.yml)
- [Naftiko Capabilities](capabilities/ruckus-one-network-management-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
