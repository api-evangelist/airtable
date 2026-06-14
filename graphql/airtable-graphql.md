# Airtable GraphQL

## Description

Airtable does not expose a native public GraphQL endpoint. Its developer platform is built exclusively on REST semantics: the core Records API, Metadata API, Webhooks API, Enterprise API, SCIM API, Audit Logs API, and Shares API all use JSON over HTTPS with standard HTTP verbs and cursor-based pagination.

## Schema Type

Conceptual data model derived from the Airtable REST API surface. The SDL in `airtable-schema.graphql` is a comprehensive representation of every resource and field type documented in the Airtable REST API. It is intended for tooling, catalog enrichment, code generation, and integration mapping — not for execution against a live GraphQL endpoint.

## Endpoint

None. No native GraphQL endpoint exists as of June 2026.

## Documentation

- API Introduction: https://airtable.com/developers/web/api/introduction
- Field Model: https://airtable.com/developers/web/api/field-model
- Webhooks Overview: https://airtable.com/developers/web/api/webhooks-overview
- GitHub Organization: https://github.com/Airtable

## Coverage

The conceptual schema covers all major resource types from the Airtable REST API:

- **Core data**: Base, Table, Field, Record, View, Attachment, Cell
- **Collaboration**: User, Collaborator, Comment, Share
- **Automation**: Webhook, WebhookPayload, WebhookNotification, WebhookCursor
- **Enterprise**: Enterprise, Workspace, UserGroup, AuditLogEvent, AuditLogRequest
- **Identity**: ScimUser, ScimGroup, ScimMeta, ScimEmail, ScimPhoneNumber
- **Field types**: All 25+ Airtable field types modeled as a union (SingleLineText, LongText, RichText, SingleSelect, MultipleSelects, Checkbox, Number, Currency, Percent, Rating, Date, DateTime, Duration, Phone, Email, Url, CollaboratorField, MultipleCollaborators, Attachment, LinkedRecord, Lookup, Count, Rollup, Formula, AutoNumber, Barcode, Button, CreatedTime, UpdatedTime, CreatedBy, LastModifiedBy, AIText)
- **Pagination**: Offset-based cursor pagination
- **Sorting and filtering**: Sort, Filter, SortDirection, FilterOperator

## Source

Derived from:
- https://airtable.com/developers/web/api/introduction
- https://airtable.com/developers/web/api/field-model
- https://airtable.com/developers/web/api/list-records
- https://airtable.com/developers/web/api/webhooks-overview
- https://airtable.com/developers/web/api/scim-overview
- https://airtable.com/developers/web/api/audit-logs-overview
