# Airtable (airtable)

Airtable is a cloud-based collaboration service that combines the simplicity of a spreadsheet with the complexity of a database. It provides APIs for managing bases, tables, records, and more.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Applications
- Collaboration
- Data
- Databases
- Low-Code
- Productivity
- Spreadsheets

## Timestamps

- **Created:** 2023-11-21T00:00:00.000Z
- **Modified:** 2026-05-19

## APIs

### Airtable API

The Airtable API can be used to integrate your data in Airtable with any external system. The API closely follows REST semantics, uses JSON to encode objects, and relies on standard HTTP codes to signal operation outcomes.

- **Human URL:** [https://airtable.com/developers/web/api/introduction](https://airtable.com/developers/web/api/introduction)
- **Base URL:** `https://api.airtable.com`

#### Tags

- Bases
- Collaborators
- Comments
- Fields
- Records
- Tables
- Views
- Webhooks

#### Properties

- [Documentation](https://airtable.com/developers/web/api/introduction)
- [Getting Started](https://support.airtable.com/docs/getting-started-with-airtables-web-api)
- [Authentication](https://airtable.com/developers/web/api/authentication)
- [Authentication](https://airtable.com/developers/web/guides/personal-access-tokens)
- [Authentication](https://airtable.com/developers/web/guides/oauth-integrations)
- [Documentation](https://airtable.com/developers/web/api/webhooks-overview)
- [AsyncAPI](asyncapi/airtable-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/Airtable/airtable.js)
- [SDK](https://www.npmjs.com/package/airtable)
- [API Reference](https://airtable.com/developers/web/api/list-records)
- [API Reference](https://airtable.com/developers/web/api/update-record)
- [Rate Limits](https://airtable.com/developers/web/api/rate-limits)
- [Errors](https://airtable.com/developers/web/api/errors)
- [Documentation](https://airtable.com/developers/web/api/cursor-pagination)
- [Documentation](https://airtable.com/developers/web/api/field-model)
- [OpenAPI](openapi/airtable-airtable-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-airtable-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-airtable-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airtable-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-webhook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Airtable Metadata API

The Airtable Metadata API provides access to base and schema management operations. You can list bases, retrieve base schemas with table and field definitions, create new bases, tables, and fields, and update table and field configurations programmatically.

- **Human URL:** [https://airtable.com/developers/web/api/list-bases](https://airtable.com/developers/web/api/list-bases)
- **Base URL:** `https://api.airtable.com/v0/meta`

#### Tags

- Bases
- Fields
- Metadata
- Schema
- Tables

#### Properties

- [Documentation](https://airtable.com/developers/web/api/list-bases)
- [Documentation](https://airtable.com/developers/web/api/get-base-schema)
- [Documentation](https://airtable.com/developers/web/api/create-base)
- [Documentation](https://airtable.com/developers/web/api/create-table)
- [Documentation](https://airtable.com/developers/web/api/create-field)
- [API Reference](https://airtable.com/developers/web/api/update-table)
- [API Reference](https://airtable.com/developers/web/api/update-field)
- [OpenAPI](openapi/airtable-metadata-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-metadata-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-metadata-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airtable-base-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-table-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-field-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-view-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Airtable Enterprise API

The Airtable Enterprise API allows enterprise teams to manage their account programmatically outside of the Admin panel. It supports managing users, updating access permissions, and managing bases, tables, and views at scale for enterprise deployments.

- **Human URL:** [https://support.airtable.com/docs/airtable-enterprise-api](https://support.airtable.com/docs/airtable-enterprise-api)
- **Base URL:** `https://api.airtable.com/v0`

#### Tags

- Admin
- Audit
- Enterprise
- Groups
- Users

#### Properties

- [Documentation](https://support.airtable.com/docs/airtable-enterprise-api)
- [API Reference](https://airtable.com/developers/web/api/get-enterprise)
- [API Reference](https://airtable.com/developers/web/api/manage-user)
- [API Reference](https://airtable.com/developers/web/api/manage-user-membership)
- [API Reference](https://airtable.com/developers/web/api/delete-user-by-id)
- [API Reference](https://airtable.com/developers/web/api/remove-user-from-enterprise)
- [API Reference](https://airtable.com/developers/web/api/get-user-group)
- [OpenAPI](openapi/airtable-enterprise-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-enterprise-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-enterprise-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airtable-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airtable-workspace-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Airtable SCIM API

The Airtable SCIM API supports the System for Cross-domain Identity Management specification for automated user and group provisioning. It enables identity providers like Okta and Microsoft Entra ID to manage user accounts and group memberships programmatically.

- **Human URL:** [https://airtable.com/developers/web/api/scim-overview](https://airtable.com/developers/web/api/scim-overview)
- **Base URL:** `https://airtable.com/scim/v2`

#### Tags

- Groups
- Identity
- Provisioning
- SCIM
- Users

#### Properties

- [Documentation](https://airtable.com/developers/web/api/scim-overview)
- [API Reference](https://airtable.com/developers/web/api/model/scim-user-schema)
- [API Reference](https://airtable.com/developers/web/api/create-scim-user)
- [API Reference](https://airtable.com/developers/web/api/get-scim-user)
- [API Reference](https://airtable.com/developers/web/api/put-scim-user)
- [API Reference](https://airtable.com/developers/web/api/delete-scim-user)
- [API Reference](https://airtable.com/developers/web/api/get-scim-group)
- [API Reference](https://airtable.com/developers/web/api/delete-scim-group)
- [Getting Started](https://support.airtable.com/docs/managing-users-via-idp-sync)
- [OpenAPI](openapi/airtable-scim-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Airtable Audit Logs API

The Airtable Audit Logs API provides programmatic access to enterprise audit logs for compliance monitoring and security tracking. It supports creating and retrieving audit log requests with event filtering by user, event type, and date range.

- **Human URL:** [https://airtable.com/developers/web/api/audit-logs-overview](https://airtable.com/developers/web/api/audit-logs-overview)
- **Base URL:** `https://api.airtable.com/v0`

#### Tags

- Audit
- Compliance
- Enterprise
- Logs
- Security

#### Properties

- [Documentation](https://airtable.com/developers/web/api/audit-logs-overview)
- [Getting Started](https://airtable.com/developers/web/api/audit-logs-integration-guide)
- [API Reference](https://airtable.com/developers/web/api/create-audit-log-request)
- [API Reference](https://airtable.com/developers/web/api/get-audit-log-request)
- [API Reference](https://airtable.com/developers/web/api/list-audit-log-requests)
- [API Reference](https://airtable.com/developers/web/api/audit-log-events)
- [API Reference](https://airtable.com/developers/web/api/audit-log-event-types)
- [Support](https://support.airtable.com/docs/accessing-enterprise-audit-logs-in-airtable)
- [OpenAPI](openapi/airtable-audit-logs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-audit-logs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-audit-logs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airtable-audit-log-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Airtable Shares API

The Airtable Shares API allows enterprise administrators to list, manage, and delete share links across an organization. It provides programmatic control over base sharing and access management.

- **Human URL:** [https://airtable.com/developers/web/api/list-shares](https://airtable.com/developers/web/api/list-shares)
- **Base URL:** `https://api.airtable.com/v0`

#### Tags

- Access
- Collaboration
- Enterprise
- Shares

#### Properties

- [API Reference](https://airtable.com/developers/web/api/list-shares)
- [API Reference](https://airtable.com/developers/web/api/manage-share)
- [API Reference](https://airtable.com/developers/web/api/delete-share)
- [OpenAPI](openapi/airtable-shares-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airtable-shares-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airtable-shares-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/airtable-share-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/airtable-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://airtable.com/developers)
- [Documentation](https://airtable.com/developers/web/api/introduction)
- [Getting Started](https://www.airtable.com/guides/scale/using-airtable-api)
- [Authentication](https://airtable.com/developers/web/api/oauth-reference)
- [Authentication](https://airtable.com/developers/web/api/scopes)
- [Authentication](https://support.airtable.com/docs/creating-personal-access-tokens)
- [Errors](https://airtable.com/developers/web/api/errors)
- [Rate Limits](https://airtable.com/developers/web/api/rate-limits)
- [Rate Limits](https://support.airtable.com/docs/managing-api-call-limits-in-airtable)
- [Changelog](https://airtable.com/developers/web/api/changelog)
- [Policies](https://support.airtable.com/docs/airtable-api-deprecation-guidelines)
- [Documentation](https://airtable.com/developers/web/api/cursor-pagination)
- [Documentation](https://airtable.com/developers/web/api/field-model)
- [Documentation](https://airtable.com/developers/web/api/change-events)
- [Blog](https://blog.airtable.com)
- [Status Page](https://status.airtable.com)
- [Support](https://support.airtable.com)
- [Terms of Service](https://airtable.com/tos)
- [Privacy Policy](https://airtable.com/privacy)
- [Pricing](https://airtable.com/pricing)
- [GitHub Organization](https://github.com/airtable)
- [Community](https://community.airtable.com)
- [Forum](https://community.airtable.com/c/developers/55)
- [Portal](https://www.airtable.com)
- [Portal](https://airtable.com/login)
- [Sign Up](https://airtable.com/signup)
- [Newsletter](http://eepurl.com/gVD-df)
- [Documentation](https://airtable.com/developers/extensions)
- [Documentation](https://airtable.com/developers/scripting/api)
- [Documentation](https://support.airtable.com/docs/airtable-enterprise-api)
- [AsyncAPI](https://support.airtable.com/docs/airtable-webhooks-api-overview) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Documentation](https://airtable.com/developers/web/guides/webhooks-api)
- [Documentation](https://support.airtable.com/docs/airtable-resources-for-developers)
- [Changelog](https://www.airtable.com/whatsnew)
- [Twitter](https://x.com/airtable)
- [LinkedIn](https://www.linkedin.com/company/airtable)
- [YouTube](https://www.youtube.com/@AirtableApp)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/airtable)
- [SDK](https://github.com/Airtable/airtable.js)
- [SDK](https://www.npmjs.com/package/airtable)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/rules/airtable-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/airtable/refs/heads/main/vocabulary/airtable-vocabulary.yaml)
- [Integrations](https://www.airtable.com/integrations)
- [M C P Server](https://github.com/Airtable/airtable-mcp-cli)
- [Agent Skill](https://github.com/Airtable/skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
**FN:** Airtable
**Email:** support@airtable.com
**URL:** https://airtable.com
