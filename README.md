# Microsoft Power Apps (microsoft-power-apps)

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
