# Microsoft Power BI (microsoft-power-bi)

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

Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides REST APIs for accessing and managing Power BI resources including reports, dashboards, datasets, and workspaces programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-power-bi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-power-bi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Microsoft
- Reports

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Power BI REST API

The Power BI REST API enables programmatic access to Power BI resources including datasets, reports, dashboards, workspaces, and dataflows. Developers can automate report deployment, manage workspace permissions, refresh datasets, export reports, and embed Power BI content in custom applications.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/power-bi/](https://learn.microsoft.com/en-us/rest/api/power-bi/)
- **Base URL:** `https://api.powerbi.com/v1.0/myorg/`

#### Tags

- Analytics
- Business Intelligence
- Dashboards
- Reports

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-bi/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/power-bi/datasets)
- [OpenAPI](openapi/microsoft-power-bi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-power-bi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-bi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Embedded API

Power BI Embedded enables developers to embed interactive Power BI reports, dashboards, and tiles into custom applications. It provides client-side JavaScript APIs for rendering and interacting with embedded content, supporting scenarios like white-label analytics, custom filtering, and programmatic report navigation.

- **Human URL:** [https://learn.microsoft.com/en-us/power-bi/developer/embedded/](https://learn.microsoft.com/en-us/power-bi/developer/embedded/)
- **Base URL:** `https://api.powerbi.com/v1.0/myorg/`

#### Tags

- Business Intelligence
- Embedded Analytics
- White Label

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-bi/developer/embedded/)
- [Postman Collection](collections/microsoft-power-bi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-bi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Admin REST API

The Power BI Admin REST API provides tenant-level administrative capabilities for managing Power BI across an organization. It enables administrators to audit user activities, manage workspaces, scan datasets for governance, retrieve tenant settings, and monitor capacity usage and performance metrics.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/power-bi/admin](https://learn.microsoft.com/en-us/rest/api/power-bi/admin)
- **Base URL:** `https://api.powerbi.com/v1.0/myorg/admin/`

#### Tags

- Administration
- Governance
- Tenant Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-bi/admin)
- [Postman Collection](collections/microsoft-power-bi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-bi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Push Datasets API

The Power BI Push Datasets API enables real-time data streaming into Power BI datasets. Developers can push rows of data directly to streaming datasets for real-time dashboard visualizations, supporting IoT scenarios, live monitoring, and event-driven analytics without requiring scheduled data refreshes.

- **Human URL:** [https://learn.microsoft.com/en-us/power-bi/developer/automation/api-automatic-retention-policy-for-real-time-data](https://learn.microsoft.com/en-us/power-bi/developer/automation/api-automatic-retention-policy-for-real-time-data)
- **Base URL:** `https://api.powerbi.com/v1.0/myorg/`

#### Tags

- Datasets
- Real-Time Data
- Streaming

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-bi/developer/automation/api-automatic-retention-policy-for-real-time-data)
- [Postman Collection](collections/microsoft-power-bi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-bi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/microsoft)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-power-bi)
- [Portal](https://app.powerbi.com/)
- [Website](https://powerbi.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [Pricing](https://powerbi.microsoft.com/en-us/pricing/)
- [Authentication](https://learn.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token)
- [S D Ks](https://learn.microsoft.com/en-us/power-bi/developer/embedded/)
- [Community](https://community.fabric.microsoft.com/t5/Power-BI-forums/ct-p/pbi_english)
- [Blog](https://powerbi.microsoft.com/en-us/blog/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Status Page](https://status.powerplatform.microsoft.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
