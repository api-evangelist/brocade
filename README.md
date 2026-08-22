# Brocade (brocade)

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

Brocade, now part of Broadcom, provides Fibre Channel networking solutions for storage area networks (SANs). The Brocade portfolio includes SAN switches, directors, Fabric OS software, and the SANnav management platform, all offering REST APIs for programmable management and automation of SAN infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/brocade/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/brocade/refs/heads/main/apis.yml)

## Tags

- Data Center
- Directors
- Fibre Channel
- Network Automation
- Networking
- SAN
- Storage Area Networks
- Switches

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-21

## APIs

### Brocade Fabric OS REST API

The Brocade Fabric OS REST API provides a programmable web-service interface for managing Brocade SAN switches across a fabric. It supports YANG-based modules for configuring and monitoring switch resources including chassis, ports, zoning, security, logging, MAPS, and Fibre Channel features. Supported on Fabric OS 8.2.0 and later.

- **Human URL:** [https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x.html](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x.html)
- **Base URL:** `https://{switch-ip}/rest`

#### Tags

- Fabric OS
- Fibre Channel
- Network Management
- SAN
- Switches

#### Properties

- [Documentation](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x.html)
- [Reference](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/10-0-x.html)
- [Authentication](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html)
- [Getting Started](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html)
- [S D Ks](https://github.com/brocade/pyfos)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brocade SANnav Management Portal REST API

The Brocade SANnav Management Portal REST API provides a programmable web-service interface for accessing and managing the SANnav Management Portal server. REST API services include Login, Discovery, FCR, Fault, Inventory, Health Summary, User Management, RBAC, Zoning, and Proxy to Fabric OS REST API. SANnav is the successor to Brocade Network Advisor for SAN management.

- **Human URL:** [https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x.html](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x.html)
- **Base URL:** `https://{sannav-host}/external-api/v1`

#### Tags

- Discovery
- Fibre Channel
- Monitoring
- SAN Management
- Zoning

#### Properties

- [Documentation](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x.html)
- [Reference](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x/SANnav-Overview.html)
- [Getting Started](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x/SANnav-Overview.html)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brocade SANnav Northbound Streaming API

The Brocade SANnav Northbound Streaming API enables real-time streaming of SAN telemetry and event data from the SANnav Management Portal to external systems. It provides northbound streaming of fault events, performance metrics, and inventory changes for integration with third-party monitoring and analytics platforms.

- **Human URL:** [https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api-and-nb-streaming/2-3-0x.html](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api-and-nb-streaming/2-3-0x.html)
- **Base URL:** `https://{sannav-host}/external-api/v1/stream`

#### Tags

- Events
- Monitoring
- SAN Management
- Streaming
- Telemetry

#### Properties

- [Documentation](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api-and-nb-streaming/2-3-0x.html)
- [Reference](https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/2-4-0x/Resources-REST-API/Stream-REST-API/GET--external-api-v1-stream-servers-REST-API.html)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brocade Network Advisor REST API

The Brocade Network Advisor REST API provided a web-services interface for configuring and monitoring Brocade SAN switches, including fabric management, topology, zoning, and performance data retrieval. Network Advisor reached end of life in March 2019 and has been replaced by SANnav Management Portal.

- **Human URL:** [https://docs.broadcom.com/doc/12395099](https://docs.broadcom.com/doc/12395099)
- **Base URL:** `https://{bna-host}/rest`

#### Tags

- Analytics
- Deprecated
- Monitoring
- SAN Management

#### Properties

- [Documentation](https://docs.broadcom.com/doc/12395099)
- [Deprecation  Notice](https://docs.broadcom.com/doc/12395099)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brocade Workflow Composer API

The Brocade Workflow Composer was a network automation platform based on StackStorm for event-driven automation and orchestration workflows. The product was transferred to Extreme Networks as part of the IP networking business acquisition and is now known as Extreme Workflow Composer.

- **Human URL:** [https://bwc-docs.brocade.com/](https://bwc-docs.brocade.com/)
- **Base URL:** `https://{bwc-host}/api/v1`

#### Tags

- Automation
- Deprecated
- Orchestration
- Workflow

#### Properties

- [Documentation](https://bwc-docs.brocade.com/)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brocade VCS Fabric API

The Brocade VCS Fabric API provided REST interfaces for Virtual Cluster Switching fabric configuration on Brocade VDX switches. The VCS Fabric product line was transferred to Extreme Networks as part of the data center networking business acquisition and is no longer part of the Broadcom Brocade portfolio.

- **Human URL:** [https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products](https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products)
- **Base URL:** `https://{switch-ip}/rest`

#### Tags

- Deprecated
- Fabric
- Switching
- VCS

#### Properties

- [Documentation](https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products)
- [Deprecation  Notice](https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products)
- [Postman Collection](collections/brocade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brocade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/brocade)
- [Portal](https://techdocs.broadcom.com/us/en/fibre-channel-networking.html)
- [Documentation](https://techdocs.broadcom.com/us/en/fibre-channel-networking.html)
- [Getting Started](https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html)
- [Support](https://www.broadcom.com/support/fibre-channel-networking)
- [Website](https://www.broadcom.com/products/fibre-channel-networking)
- [Sign Up](https://www.broadcom.com/support/fibre-channel-networking)
- [Login](https://www.broadcom.com/support/fibre-channel-networking)
- [Terms of Service](https://www.broadcom.com/company/legal/terms-of-use)
- [Privacy Policy](https://www.broadcom.com/company/legal/privacy/policy)
- [Community](https://community.broadcom.com/t5/Fibre-Channel-SAN-Forums/bd-p/fibre)
- [Blog](https://community.broadcom.com/landingpage/brocade-community)
- [GitHub Organization](https://github.com/brocade)
- [S D Ks](https://github.com/brocade/pyfos)
- [Changelog](https://www.broadcom.com/support/fibre-channel-networking/eol)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
