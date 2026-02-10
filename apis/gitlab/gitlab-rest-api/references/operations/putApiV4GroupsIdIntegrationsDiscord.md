# PUT /api/v4/groups/{id}/integrations/discord

**Resource:** [Integrations](../resources/Integrations.md)
**Create/Edit Discord integration**
**Operation ID:** `putApiV4GroupsIdIntegrationsDiscord`

Set Discord integration.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesIntegrationBasic](../schemas/APIEntitiesIntegrationBasic/APIEntitiesIntegrationBasic.md)

