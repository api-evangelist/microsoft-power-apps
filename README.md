# Microsoft Power Apps APIs (microsoft-power-apps)
Collection of APIs for Microsoft Power Apps platform enabling low-code application development, automation, and data connectivity.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Business Applications, Cloud, Enterprise, Low-Code, Microsoft, No-Code, Power Platform, SaaS

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Dataverse API (Common Data Service)
RESTful API for interacting with Microsoft Dataverse for data storage and management.

**Human URL:** [https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)

#### Tags:

 - CRM, Data Platform, Database, REST API

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- [OpenAPI](openapi/microsoft-power-apps-dataverse-web-api-openapi.yml)
- [JSONSchema](json-schema/microsoft-power-apps-entity-schema.json)
- [JSONLD](json-ld/microsoft-power-apps-context.jsonld)
- [Authentication](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth)

## Common Properties

- [DeveloperPortal](https://docs.microsoft.com/en-us/power-apps/developer/)
- [Blog](https://powerapps.microsoft.com/blog/)
- [Pricing](https://powerapps.microsoft.com/pricing/)
- [StatusPage](https://status.powerplatform.microsoft.com/)
- [Support](https://powerapps.microsoft.com/support/)
- [Training](https://docs.microsoft.com/en-us/learn/powerplatform/power-apps)
- [GitHubRepository](https://github.com/microsoft/PowerApps-Samples)
- [TermsOfService](https://www.microsoft.com/licensing/terms/productoffering/MicrosoftPowerApps)
- [PrivacyPolicy](https://privacy.microsoft.com/)
- [CLI](https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/pipeline)
- [Security](https://learn.microsoft.com/en-us/power-platform/admin/wp-security)
- [ReleaseNotes](https://learn.microsoft.com/en-us/power-platform/release-plan/2025wave1/power-apps/planned-features)

## Features

| Name | Description |
|------|-------------|
| Low-Code Development | Visual drag-and-drop app building with Power Fx formulas and pre-built templates. |
| Microsoft Dataverse | Built-in data platform with security, business logic, and integration capabilities. |
| Custom Connectors | Connect to any external API through standard and custom connector definitions. |
| Model-Driven Apps | Automatically generated UIs based on data model and business logic configuration. |
| Component Framework | Professional code components using TypeScript for custom controls in canvas and model-driven apps. |

## Use Cases

| Name | Description |
|------|-------------|
| Business Process Automation | Digitize paper-based processes and manual workflows with custom business applications. |
| Customer Portal | Build external-facing portals using Power Pages with Dataverse Web API integration. |
| Field Service Apps | Create mobile applications for field workers with offline capabilities and data sync. |
| Data Management | Build CRUD applications on Dataverse for managing business data with role-based security. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft 365 | Native integration with Teams, SharePoint, Outlook, and Excel for productivity workflows. |
| Dynamics 365 | Shared Dataverse platform with Dynamics 365 CRM and ERP modules for unified data. |
| Power Automate | Trigger automated flows from Power Apps for cross-system process automation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Microsoft Dataverse Web API](openapi/microsoft-power-apps-dataverse-web-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Dataverse Web API](capabilities/shared/dataverse-web-api.yaml) -- 12 operations for account, contact, and entity CRUD management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Platform](capabilities/data-platform.yaml) | Dataverse Web API | 12 | Power Platform Developer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
