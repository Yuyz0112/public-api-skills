# GET /api/v4/groups/{id}/integrations

**Resource:** [Integrations](../resources/Integrations.md)
**List all active integrations**
**Operation ID:** `getApiV4GroupsIdIntegrations`

Get a list of all active integrations.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIntegrationBasic](../schemas/APIEntitiesIntegrationBasic/APIEntitiesIntegrationBasic.md)

