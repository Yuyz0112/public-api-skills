# PUT /api/v4/groups/{id}/integrations/redmine

**Resource:** [Integrations](../resources/Integrations.md)
**Create/Edit Redmine integration**
**Operation ID:** `putApiV4GroupsIdIntegrationsRedmine`

Set Redmine integration.

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

