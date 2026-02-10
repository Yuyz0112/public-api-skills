# DELETE /api/v4/projects/{id}/integrations/{slug}

**Resource:** [Integrations](../resources/Integrations.md)
**Disable an integration**
**Operation ID:** `deleteApiV4ProjectsIdIntegrationsSlug`

Disable the integration. Integration settings are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | enum: apple-app-store, asana, assembla... | Yes | The name of the integration |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

