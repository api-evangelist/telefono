# Telefono (telefono)

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

Telefono is a phone number intelligence and validation API platform providing real-time phone number lookup, validation, carrier information, line type detection, and number formatting services for developers. The platform helps businesses verify user phone numbers, detect fraud, improve deliverability of SMS campaigns, and enrich contact data with carrier and geographic information.

**APIs.json:** [https://www.telefono.com](https://www.telefono.com)

## Scope

- **Type:** Index

## Tags

- Carrier Lookup
- Data Enrichment
- Fraud Prevention
- Number Intelligence
- Number Verification
- Phone Lookup
- Phone Validation
- Telecommunications

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Telefono Phone Validation API

Validate phone numbers in real-time to determine if they are valid, active, and reachable. Returns validity status, number type (mobile, landline, VoIP, toll-free), formatted number in E.164 and national formats, country information, and whether the number is likely a virtual or disposable number.

- **Human URL:** [https://developers.telefono.com/validation](https://developers.telefono.com/validation)
- **Base URL:** `https://api.telefono.com/v1/validate`

#### Tags

- E.164 Format
- Number Formatting
- Number Verification
- Phone Validation
- Real-Time Validation

#### Properties

- [Documentation](https://developers.telefono.com/validation)
- [OpenAPI](openapi/telefono-validation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefono-validation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefono-validation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefono.com/authentication)
- [Getting Started](https://developers.telefono.com/getting-started)
- [Pricing](https://www.telefono.com/pricing)
- [Rate Limits](https://developers.telefono.com/rate-limits)

### Telefono Carrier Lookup API

Look up carrier and network information for any phone number worldwide. Returns the current carrier name, network type (GSM, CDMA, UMTS, LTE, 5G), mobile country code (MCC), mobile network code (MNC), and roaming status. Supports real-time HLR (Home Location Register) lookups for accurate portability-aware carrier detection.

- **Human URL:** [https://developers.telefono.com/carrier](https://developers.telefono.com/carrier)
- **Base URL:** `https://api.telefono.com/v1/carrier`

#### Tags

- Carrier Detection
- Carrier Lookup
- HLR
- MCC MNC
- Network Type
- Telecommunications

#### Properties

- [Documentation](https://developers.telefono.com/carrier)
- [OpenAPI](openapi/telefono-carrier-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefono-carrier.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefono-carrier.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefono.com/authentication)
- [Pricing](https://www.telefono.com/pricing/carrier)

### Telefono Number Formatting API

Format phone numbers consistently across different national and international formats. Convert between E.164, national, international, and RFC3966 formats. Supports parsing of phone numbers with country code hints, extracting country codes, and generating click-to-call compatible URIs.

- **Human URL:** [https://developers.telefono.com/format](https://developers.telefono.com/format)
- **Base URL:** `https://api.telefono.com/v1/format`

#### Tags

- E.164
- International Format
- National Format
- Number Formatting
- Phone Parsing

#### Properties

- [Documentation](https://developers.telefono.com/format)
- [OpenAPI](openapi/telefono-format-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefono-format.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefono-format.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefono.com/authentication)

## Common Properties

- [Authentication](https://developers.telefono.com/authentication)
- [Getting Started](https://developers.telefono.com/getting-started)
- [Rate Limits](https://developers.telefono.com/rate-limits)
- [Sign Up](https://www.telefono.com/signup)
- [Pricing](https://www.telefono.com/pricing)
- [Terms of Service](https://www.telefono.com/terms)
- [Privacy Policy](https://www.telefono.com/privacy)
- [Status Page](https://status.telefono.com)
- [Support](https://www.telefono.com/support)
- [Git Hub](https://github.com/telefono-api)

## Maintainers

**Email:** api@telefono.com
