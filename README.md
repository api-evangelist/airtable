# Airtable (airtable)
Airtable is a cloud-based collaboration service that combines the simplicity of a spreadsheet with the complexity of a database. It provides APIs for managing bases, tables, records, and more, enabling developers to integrate Airtable with any external system. Airtable offers REST API, Webhooks, SCIM, Enterprise, and Audit Log APIs for both builders and enterprise administrators.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Applications, Collaboration, Data, Databases, Low-Code, Productivity, Spreadsheets

## Timestamps

- **Created:** 2023-11-21
- **Modified:** 2026-04-19

## APIs

### Airtable API
The Airtable API can be used to integrate your data in Airtable with any external system. The API closely follows REST semantics, uses JSON to encode objects, and relies on standard HTTP codes to signal operation outcomes.

**Human URL:** [https://airtable.com/developers/web/api/introduction](https://airtable.com/developers/web/api/introduction)

#### Tags:

 - Bases, Collaborators, Comments, Fields, Records, Tables, Views, Webhooks

#### Properties

- [Documentation](https://airtable.com/developers/web/api/introduction)
- [OpenAPI](openapi/airtable-airtable-api-openapi.yml)
- [JSONSchema - Record](json-schema/airtable-record-schema.json)
- [JSONSchema - Comment](json-schema/airtable-comment-schema.json)
- [JSONSchema - Webhook](json-schema/airtable-webhook-schema.json)
- [JSON-LD](json-ld/airtable-context.jsonld)

### Airtable Metadata API
The Airtable Metadata API provides access to base and schema management operations. You can list bases, retrieve base schemas with table and field definitions, create new bases, tables, and fields, and update table and field configurations programmatically.

**Human URL:** [https://airtable.com/developers/web/api/list-bases](https://airtable.com/developers/web/api/list-bases)

#### Tags:

 - Bases, Fields, Metadata, Schema, Tables

#### Properties

- [Documentation](https://airtable.com/developers/web/api/list-bases)
- [OpenAPI](openapi/airtable-metadata-api-openapi.yml)
- [JSONSchema - Base](json-schema/airtable-base-schema.json)
- [JSONSchema - Table](json-schema/airtable-table-schema.json)
- [JSONSchema - Field](json-schema/airtable-field-schema.json)
- [JSONSchema - View](json-schema/airtable-view-schema.json)

### Airtable Enterprise API
The Airtable Enterprise API allows enterprise teams to manage their account programmatically outside of the Admin panel. It supports managing users, updating access permissions, and managing bases, tables, and views at scale.

**Human URL:** [https://support.airtable.com/docs/airtable-enterprise-api](https://support.airtable.com/docs/airtable-enterprise-api)

#### Tags:

 - Admin, Audit, Enterprise, Groups, Users

#### Properties

- [Documentation](https://support.airtable.com/docs/airtable-enterprise-api)
- [OpenAPI](openapi/airtable-enterprise-api-openapi.yml)
- [JSONSchema - User](json-schema/airtable-user-schema.json)
- [JSONSchema - Workspace](json-schema/airtable-workspace-schema.json)

### Airtable SCIM API
The Airtable SCIM API supports the System for Cross-domain Identity Management specification for automated user and group provisioning. It enables identity providers like Okta and Microsoft Entra ID to manage user accounts and group memberships programmatically.

**Human URL:** [https://airtable.com/developers/web/api/scim-overview](https://airtable.com/developers/web/api/scim-overview)

#### Tags:

 - Groups, Identity, Provisioning, SCIM, Users

#### Properties

- [Documentation](https://airtable.com/developers/web/api/scim-overview)
- [OpenAPI](openapi/airtable-scim-api-openapi.yml)

### Airtable Audit Logs API
The Airtable Audit Logs API provides programmatic access to enterprise audit logs for compliance monitoring and security tracking.

**Human URL:** [https://airtable.com/developers/web/api/audit-logs-overview](https://airtable.com/developers/web/api/audit-logs-overview)

#### Tags:

 - Audit, Compliance, Enterprise, Logs, Security

#### Properties

- [Documentation](https://airtable.com/developers/web/api/audit-logs-overview)
- [OpenAPI](openapi/airtable-audit-logs-api-openapi.yml)
- [JSONSchema - Audit Log Event](json-schema/airtable-audit-log-event-schema.json)

### Airtable Shares API
The Airtable Shares API allows enterprise administrators to list, manage, and delete share links across an organization.

**Human URL:** [https://airtable.com/developers/web/api/list-shares](https://airtable.com/developers/web/api/list-shares)

#### Tags:

 - Access, Collaboration, Enterprise, Shares

#### Properties

- [Documentation](https://airtable.com/developers/web/api/list-shares)
- [OpenAPI](openapi/airtable-shares-api-openapi.yml)
- [JSONSchema - Share](json-schema/airtable-share-schema.json)

## Common Properties

- [Portal](https://airtable.com/developers)
- [Documentation](https://airtable.com/developers/web/api/introduction)
- [GettingStarted](https://www.airtable.com/guides/scale/using-airtable-api)
- [Authentication](https://airtable.com/developers/web/api/oauth-reference)
- [RateLimits](https://airtable.com/developers/web/api/rate-limits)
- [ChangeLog](https://airtable.com/developers/web/api/changelog)
- [Blog](https://blog.airtable.com)
- [StatusPage](https://status.airtable.com)
- [Support](https://support.airtable.com)
- [TermsOfService](https://airtable.com/tos)
- [PrivacyPolicy](https://airtable.com/privacy)
- [Pricing](https://airtable.com/pricing)
- [GitHubOrganization](https://github.com/airtable)
- [Community](https://community.airtable.com)
- [SignUp](https://airtable.com/signup)
- [Newsletter](http://eepurl.com/gVD-df)
- [Twitter](https://x.com/airtable)
- [LinkedIn](https://www.linkedin.com/company/airtable)
- [YouTube](https://www.youtube.com/@AirtableApp)
- [StackOverflow](https://stackoverflow.com/questions/tagged/airtable)
- [SDK](https://github.com/Airtable/airtable.js)
- [SDK - npm](https://www.npmjs.com/package/airtable)
- [SpectralRules](rules/airtable-spectral-rules.yml)
- [NaftikoCapability - Database Management](capabilities/database-management.yaml)
- [Vocabulary](vocabulary/airtable-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| No-Code Database | Spreadsheet-database hybrid for non-technical users to build databases without code. |
| REST API | Full REST API for creating, reading, updating, and deleting records programmatically. |
| Webhooks | Real-time event notifications when records change. |
| OAuth 2.0 | Secure OAuth 2.0 integration for third-party apps. |
| SCIM Provisioning | Enterprise user provisioning via SCIM for Okta, Entra ID, and other IdPs. |
| Audit Logs | Enterprise audit logs for compliance and security monitoring. |
| Extensions | Custom UI extensions and scripting for advanced functionality. |
| Automations | Built-in workflow automation with triggers and actions. |

## Use Cases

| Name | Description |
|------|-------------|
| Project Management | Track tasks, milestones, and team assignments in structured databases. |
| CRM | Build custom CRM systems for tracking contacts, deals, and pipelines. |
| Content Management | Manage editorial calendars, content assets, and publishing workflows. |
| Inventory Management | Track inventory, orders, and supply chain data. |
| Event Planning | Coordinate event logistics, attendees, and schedules. |
| HR & Recruiting | Manage job applicants, employee records, and onboarding processes. |

## Integrations

| Name | Description |
|------|-------------|
| Zapier | Connect Airtable to 5000+ apps via Zapier automations. |
| Make (Integromat) | Visual automation builder for complex Airtable workflows. |
| Slack | Send Airtable notifications and updates to Slack channels. |
| Salesforce | Sync Airtable data with Salesforce CRM. |
| GitHub | Link Airtable records to GitHub issues and pull requests. |
| Okta | Enterprise SSO and SCIM provisioning via Okta. |
| Google Workspace | Import from Google Sheets and sync with Google Drive. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Airtable API](openapi/airtable-airtable-api-openapi.yml)
- [Airtable Metadata API](openapi/airtable-metadata-api-openapi.yml)
- [Airtable Enterprise API](openapi/airtable-enterprise-api-openapi.yml)
- [Airtable SCIM API](openapi/airtable-scim-api-openapi.yml)
- [Airtable Audit Logs API](openapi/airtable-audit-logs-api-openapi.yml)
- [Airtable Shares API](openapi/airtable-shares-api-openapi.yml)

### JSON Schema

- [Record](json-schema/airtable-record-schema.json)
- [Comment](json-schema/airtable-comment-schema.json)
- [Webhook](json-schema/airtable-webhook-schema.json)
- [Base](json-schema/airtable-base-schema.json)
- [Table](json-schema/airtable-table-schema.json)
- [Field](json-schema/airtable-field-schema.json)
- [View](json-schema/airtable-view-schema.json)
- [User](json-schema/airtable-user-schema.json)
- [Workspace](json-schema/airtable-workspace-schema.json)
- [Audit Log Event](json-schema/airtable-audit-log-event-schema.json)
- [Share](json-schema/airtable-share-schema.json)

### JSON Structure

- [Record Structure](json-structure/airtable-record-structure.json)
- [Comment Structure](json-structure/airtable-comment-structure.json)
- [Webhook Structure](json-structure/airtable-webhook-structure.json)
- [Base Structure](json-structure/airtable-base-structure.json)
- [Table Structure](json-structure/airtable-table-structure.json)
- [Field Structure](json-structure/airtable-field-structure.json)
- [View Structure](json-structure/airtable-view-structure.json)
- [User Structure](json-structure/airtable-user-structure.json)
- [Workspace Structure](json-structure/airtable-workspace-structure.json)
- [Audit Log Event Structure](json-structure/airtable-audit-log-event-structure.json)
- [Share Structure](json-structure/airtable-share-structure.json)

### JSON-LD

- [Airtable Context](json-ld/airtable-context.jsonld)

### Examples

- [Record Example](examples/airtable-record-example.json)
- [Base Example](examples/airtable-base-example.json)
- [Table Example](examples/airtable-table-example.json)
- [Field Example](examples/airtable-field-example.json)
- [View Example](examples/airtable-view-example.json)
- [User Example](examples/airtable-user-example.json)
- [Workspace Example](examples/airtable-workspace-example.json)
- [Audit Log Event Example](examples/airtable-audit-log-event-example.json)
- [Share Example](examples/airtable-share-example.json)
- [Comment Example](examples/airtable-comment-example.json)
- [Webhook Example](examples/airtable-webhook-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Airtable API](capabilities/shared/airtable-api.yaml) — 4 operations for records management
- [Airtable Metadata API](capabilities/shared/airtable-metadata-api.yaml) — 2 operations for schema browsing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Database Management](capabilities/database-management.yaml) | Airtable API, Metadata API | 6 | Developer, Data Analyst |

## Vocabulary

- [Airtable Vocabulary](vocabulary/airtable-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Airtable Spectral Rules](rules/airtable-spectral-rules.yml) — 26 rules across 9 categories enforcing Airtable API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
