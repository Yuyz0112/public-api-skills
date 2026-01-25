# GET /extension_schemas/{id}

**Resource:** [Extension Schemas](../resources/Extension-Schemas.md)
**Get an extension vendor**
**Operation ID:** `getExtensionSchema`

Get details about one specific extension vendor.

A PagerDuty extension vendor represents a specific type of outbound extension such as Generic Webhook, Slack, ServiceNow.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extension-schemas)

Scoped OAuth requires: `extension_schemas.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The extension vendor requested |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

