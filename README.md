# Ketch (ketch-io)

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

Ketch is a data permissioning and consent platform that helps enterprises keep customer data clean, permissioned, and AI-ready across web, mobile, and backend systems. Its products span consent management, data subject rights automation, AI-powered data mapping, marketing preference management, risk and reporting, a Data Sentry privacy pentest, and an AI governance layer. The Ketch Agent Network turns privacy program insights into agent-driven actions. Builders use a public REST API hosted at global.ketchapi.com, web and mobile SDKs published on GitHub, and Google Tag Manager templates to enforce consent at the source. Ketch advertises more than 1,000 pre-built API integrations with systems, apps, and AI models, with a free tier alongside enterprise and mid-market editions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ketch-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ketch-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Ketch
- Privacy
- Consent
- Preference Management
- DSR
- Data Mapping
- AI Governance
- GDPR
- CCPA
- SDK
- Mobile
- Web

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Ketch API

REST API for the Ketch platform that powers consent collection and enforcement, data subject rights workflows, data mapping, preference management, and risk reporting. Endpoints are served from global.ketchapi.com and include the Harbormaster service used for authentication and OAuth integration with documentation. Webhooks and a large catalog of pre-built integrations are available for connecting downstream systems.

- **Human URL:** [https://docs.ketch.com/](https://docs.ketch.com/)
- **Base URL:** `https://global.ketchapi.com`

#### Tags

- Consent
- DSR
- Preferences
- Data Mapping
- Webhooks

#### Properties

- [Documentation](https://docs.ketch.com/)
- [API Reference](https://docs.ketch.com/ketch/reference)
- [Integrations](https://www.ketch.com/integrations)
- [Source Code](https://github.com/ketch-com)
- [Sign Up](https://www.ketch.com/ketch-free-cookie-banner)
- [Pricing](https://www.ketch.com/pricing)
- [Postman Collection](collections/ketch-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ketch-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ketch Web SDK

TypeScript and JavaScript Web API and consent library for collecting, storing, and enforcing consent in browser environments. Includes methods such as getBootstrapConfiguration and getConsent and a consent library distributed via GitHub.

- **Human URL:** [https://github.com/ketch-sdk](https://github.com/ketch-sdk)

#### Tags

- Web
- JavaScript
- TypeScript
- SDK
- Consent

#### Properties

- [Source Code](https://github.com/ketch-sdk/ketch-web-api)
- [Consent Library](https://github.com/ketch-sdk/ketch-consent)
- [Documentation](https://docs.ketch.com/)
- [Postman Collection](collections/ketch-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ketch-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ketch Mobile SDKs

Native iOS and Android SDKs for collecting and enforcing consent in mobile apps. The iOS SDK supports iOS 15 and above; the Android SDK targets API level 26 and above. Supports preemptive consent collection and WebView-based consent management and DSR submission.

- **Human URL:** [https://github.com/ketch-com](https://github.com/ketch-com)

#### Tags

- Mobile
- iOS
- Android
- SDK
- Consent

#### Properties

- [i O S](https://github.com/ketch-com/ketch-ios)
- [Android](https://github.com/ketch-com/ketch-android)
- [Documentation](https://developers.ketch.com/docs/mobile-implementation)
- [Postman Collection](collections/ketch-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ketch-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.ketch.com/)
- [Documentation](https://docs.ketch.com/)
- [Source Code](https://github.com/ketch-sdk)
- [Source Code](https://github.com/ketch-com)
- [Pricing](https://www.ketch.com/pricing)
- [Integrations](https://www.ketch.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
