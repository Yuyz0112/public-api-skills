# GET /extension_schemas

**Resource:** [Extension Schemas](../resources/Extension-Schemas.md)
**List extension schemas**
**Operation ID:** `listExtensionSchemas`

List all extension schemas.

A PagerDuty extension vendor represents a specific type of outbound extension such as Generic Webhook, Slack, ServiceNow.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extension-schemas)

Scoped OAuth requires: `extension_schemas.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of extension schemas. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

