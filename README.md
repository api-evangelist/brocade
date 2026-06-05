# Brocade (brocade)

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
