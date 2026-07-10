# Jenesis Software (jenesis-software)

Jenesis Software is a web-based insurance agency management system (AMS) built for independent property and casualty agencies. It helps agents manage existing clients, market to prospects, and run day-to-day operations - client and policy management, a pre-fillable ACORD form library, carrier downloads (IVANS/Ebix), comparative rating, two-way email and texting, commission tracking, receipts and payments, e-signature, invoicing, and reporting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jenesis-software/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jenesis-software/refs/heads/main/apis.yml)

## Access Model - No Public Developer API

Jenesis Software does **not** publish a public, self-serve developer API. There is no developer portal, no API reference, no OpenAPI description, no SDK, and no WebSocket endpoint documented on jenesissoftware.com as of this writing. Jenesis's own integration guidance states directly that it does not offer an open API.

Instead, Jenesis connects to outside systems through **vendor-built connectors and partner platforms**, each arranged and provisioned through Jenesis rather than exposed as documented REST endpoints:

- **Zapier** via the **JenesisLink** integration (for example, JenesisNow to GoHighLevel for pipeline, marketing automation, and appointment scheduling)
- **IVANS** and **Ebix TEAM-UP** ACORD-standard carrier data downloads (and **Brovada/Acturis** in Canada)
- **Zywave / TurboRater** comparative rating
- **DocuSign**, **Formstack Sign**, **WeSignature** for e-signature
- **QuickBooks** (Desktop and Online), **RingCentral**, **Lightspeed Voice**, **Twilio**, **Imperial PFS**, and payment processors (**Simply Easier Payments**, **WeSignature Payments**)

Because there is no documented public API, the API areas below are **modeled** from Jenesis's published product capabilities and integration surface. They describe the logical data domains an agency works with in Jenesis - they do **not** correspond to documented public endpoints, and no base URL or path is asserted for them (`endpointsModeled: true`).

## Tags

- Insurance
- Agency Management System
- InsurTech
- Property and Casualty
- Policy Management
- ACORD
- Carrier Downloads
- No Public API

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## APIs (Modeled)

### Jenesis Software Clients API

Modeled capability area for clients and prospects (contacts, households, pipeline). Reached by outside systems only through partner connectors such as JenesisLink/Zapier - not a documented public REST API.

- **Human URL:** [https://www.jenesissoftware.com/integrations/](https://www.jenesissoftware.com/integrations/)

### Jenesis Software Policies API

Modeled capability area for policies, coverage, endorsements, and renewals. Policy data is populated largely by carrier downloads (IVANS/Ebix) and comparative raters. No documented public REST API.

- **Human URL:** [https://www.jenesissoftware.com/integrations/](https://www.jenesissoftware.com/integrations/)

### Jenesis Software Carriers API

Modeled capability area for carrier connectivity and downloads via IVANS, Ebix TEAM-UP, and Brovada/Acturis. These are industry data-exchange integrations provisioned through Jenesis, not a public developer API.

- **Human URL:** [https://www.jenesissoftware.com/integrations/](https://www.jenesissoftware.com/integrations/)

### Jenesis Software Documents API

Modeled capability area for documents, ACORD forms, media attachments, and e-signature (DocuSign, Formstack Sign, WeSignature). Handled inside the AMS and via partner connectors, not a public REST API.

- **Human URL:** [https://www.jenesissoftware.com/integrations/](https://www.jenesissoftware.com/integrations/)

## Pricing

Jenesis deliberately does not publish exact pricing on its own site and directs prospects to schedule a demo or contact sales. Third-party aggregators report per-user, tiered pricing (for example, a Basic tier around $50/user/month plus a per-location fee, and a Pro/Advanced tier around $70/user/month plus a per-location fee). Those figures are third-party-reported, not official Jenesis published pricing, and are noted here only for context - no `plans/` file is included because Jenesis publishes no authoritative pricing artifact.

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/jenesis-software)
- [Website](https://www.jenesissoftware.com/)
- [Documentation (Integrations)](https://www.jenesissoftware.com/integrations/)
- [X](https://twitter.com/jenesissoftware)
- [Facebook](https://www.facebook.com/JenesisSoftware)
- [YouTube](https://www.youtube.com/@Jenesissoftware)
- [Blog](https://www.jenesissoftware.com/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
