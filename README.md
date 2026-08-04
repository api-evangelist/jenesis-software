# Jenesis Software (jenesis-software)

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
