# GET /api/v4/projects/{id}/integrations/{slug}

**Resource:** [Integrations](../resources/Integrations.md)
**Get an integration settings**
**Operation ID:** `getApiV4ProjectsIdIntegrationsSlug`

Get the integration settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | enum: apple-app-store, asana, assembla... | Yes | The name of the integration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIntegration](../schemas/APIEntitiesIntegration/APIEntitiesIntegration.md)

