# Microsoft Power Apps (microsoft-power-apps)

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

Collection of APIs for Microsoft Power Apps platform enabling low-code application development, automation, and data connectivity.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml)

## Tags

- Business Applications
- Cloud
- Enterprise
- Low-Code
- Microsoft
- No-Code
- Power Platform
- SaaS

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Power Apps API

Core API for managing Power Apps applications, including creating, updating, and deleting apps.

- **Human URL:** [https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- **Base URL:** `https://api.powerapps.com`

#### Tags

- Applications
- Development
- Low-Code
- Power Platform

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference)
- [OpenAPI](https://docs.microsoft.com/en-us/connectors/powerappsforappmakers/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate)
- [Rate Limits](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/api-limits)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/power-platform/powerapps/apps)
- [Getting Started](https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dataverse API (Common Data Service)

RESTful API for interacting with Microsoft Dataverse (formerly Common Data Service) for data storage and management.

- **Human URL:** [https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- **Base URL:** `https://[organization].api.crm.dynamics.com/api/data/v9.2`

#### Tags

- CRM
- Data Platform
- Database
- REST API

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- [OpenAPI](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [O Data](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/query-data-web-api)
- [Authentication](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth)
- [API Reference](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/about)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/perform-operations-web-api)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-types-operations)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/custom-api)
- [OpenAPI](openapi/microsoft-power-apps-dataverse-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/microsoft-power-apps-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-power-apps-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Security](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/security-roles)
- [Training](https://learn.microsoft.com/en-us/training/modules/dataverse-web-api/)

### Power Apps Management API

API for administrative tasks including environment management, app sharing, and user permissions.

- **Human URL:** [https://docs.microsoft.com/en-us/power-platform/admin/programmability-admin-center](https://docs.microsoft.com/en-us/power-platform/admin/programmability-admin-center)
- **Base URL:** `https://api.bap.microsoft.com`

#### Tags

- Administration
- Environments
- Governance
- Management

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-platform/admin/programmability-admin-center)
- [SDK](https://docs.microsoft.com/en-us/power-platform/admin/powershell-getting-started)
- [C L I](https://docs.microsoft.com/en-us/power-platform/developer/cli/introduction)
- [Authentication](https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-management-settings)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-managed-governance/enable-managed-environment)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Apps Connectors API

API for working with custom and standard connectors to integrate external services and data sources.

- **Human URL:** [https://docs.microsoft.com/en-us/connectors/custom-connectors/](https://docs.microsoft.com/en-us/connectors/custom-connectors/)
- **Base URL:** `https://api.powerapps.com/providers/Microsoft.PowerApps`

#### Tags

- Connectors
- Custom Connectors
- Integration

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/connectors/custom-connectors/create-web-api-connector)
- [Documentation](https://docs.microsoft.com/en-us/connectors/connector-reference/)
- [Documentation](https://docs.microsoft.com/en-us/connectors/custom-connectors/)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/power-platform/connectivity/connectors/list-connectors)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Apps Canvas Apps API

API specific to Canvas Apps for creating pixel-perfect user interfaces with drag-and-drop functionality.

- **Human URL:** [https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/](https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/)
- **Base URL:** `https://api.powerapps.com`

#### Tags

- Canvas Apps
- Low-Code
- Mobile
- UI

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/dev-enterprise-intro)
- [Documentation](https://docs.microsoft.com/en-us/power-platform/power-fx/formula-reference)
- [Documentation](https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/application-lifecycle-management)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/overview)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-canvas-apps)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Apps Model-driven Apps API

API for Model-driven Apps that automatically generate UI based on data model and business logic.

- **Human URL:** [https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/](https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/)
- **Base URL:** `https://[organization].crm.dynamics.com`

#### Tags

- Business Logic
- Forms
- Model-Driven Apps
- Views

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/overview)
- [API Reference](https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/reference)
- [Documentation](https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/customize-entity-forms)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-model-driven-apps)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Apps Component Framework (PCF) API

Framework API for professional developers to create reusable code components for model-driven and canvas apps using TypeScript and web technologies.

- **Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview)
- **Base URL:** `https://api.powerapps.com`

#### Tags

- Code Components
- Component Framework
- Custom Controls
- PCF
- TypeScript

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview)
- [API Reference](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/reference/)
- [Getting Started](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/implementing-controls-using-typescript)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/create-custom-controls-using-pcf)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/bring-intelligence-using-agent-apis)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Platform REST API

Unified RESTful API for Power Platform administration including environment management, governance, licensing, app management, and capacity reporting.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/power-platform/](https://learn.microsoft.com/en-us/rest/api/power-platform/)
- **Base URL:** `https://api.powerplatform.com`

#### Tags

- Administration
- Environments
- Governance
- Licensing
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/)
- [Getting Started](https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started)
- [Authentication](https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/appmanagement/applications)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-management-settings)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-platform/connectivity/connectors/list-connectors)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Pages Web API

Web API for Power Pages (formerly Power Apps Portals) enabling CRUD operations on Dataverse tables from external-facing portal web pages.

- **Human URL:** [https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview](https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview)
- **Base URL:** `https://[site-url]/_api`

#### Tags

- CRUD
- External Users
- Portals
- Power Pages
- Web API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview)
- [Documentation](https://learn.microsoft.com/en-us/power-pages/configure/read-operations)
- [Documentation](https://learn.microsoft.com/en-us/power-pages/configure/write-update-delete-operations)
- [Tutorials](https://learn.microsoft.com/en-us/power-apps/maker/portals/webapi-tutorial)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-power-pages)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dataverse Organization Service SDK

.NET SDK providing strongly-typed access to Microsoft Dataverse through the IOrganizationService interface for server-side development and plugins.

- **Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview)
- **Base URL:** `https://[organization].api.crm.dynamics.com`

#### Tags

- .NET
- Organization Service
- Plugins
- SDK
- Server-Side

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview)
- [API Reference](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/iorganizationservice-interface)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/use-messages)
- [API Reference](https://learn.microsoft.com/en-us/dotnet/api/microsoft.powerplatform.dataverse.client.serviceclient)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Apps Code Apps API

API and SDK for building code-first Power Apps using popular frameworks like React and Vue, developed in any code-first IDE and deployed to Power Apps.

- **Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/code-apps/overview](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/overview)
- **Base URL:** `https://api.powerapps.com`

#### Tags

- Code Apps
- Code-First
- Pro Developer
- React
- Vue

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/overview)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/architecture)
- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/how-to/alm)
- [Security](https://learn.microsoft.com/en-us/power-apps/developer/code-apps/how-to/content-security-policy)
- [Postman Collection](collections/microsoft-power-apps-dataverse-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-apps-dataverse-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer Portal](https://docs.microsoft.com/en-us/power-apps/developer/)
- [Community](https://powerusers.microsoft.com/)
- [Blog](https://powerapps.microsoft.com/blog/)
- [Pricing](https://powerapps.microsoft.com/pricing/)
- [Status Page](https://status.powerplatform.microsoft.com/)
- [Support](https://powerapps.microsoft.com/support/)
- [Training](https://docs.microsoft.com/en-us/learn/powerplatform/power-apps)
- [GitHub Repository](https://github.com/microsoft/PowerApps-Samples)
- [Terms of Service](https://www.microsoft.com/licensing/terms/productoffering/MicrosoftPowerApps)
- [Privacy Policy](https://privacy.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/alm/)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/alm/pipelines)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/developer/)
- [C L I](https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/pipeline)
- [Security](https://learn.microsoft.com/en-us/power-platform/admin/wp-security)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/overview)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-overview)
- [Training](https://learn.microsoft.com/en-us/training/paths/simplify-power-platform-deployments/)
- [Release Notes](https://learn.microsoft.com/en-us/power-platform/release-plan/2025wave1/power-apps/planned-features)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
