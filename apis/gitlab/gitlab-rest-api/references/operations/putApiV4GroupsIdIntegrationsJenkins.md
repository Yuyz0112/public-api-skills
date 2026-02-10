# PUT /api/v4/groups/{id}/integrations/jenkins

**Resource:** [Integrations](../resources/Integrations.md)
**Create/Edit Jenkins integration**
**Operation ID:** `putApiV4GroupsIdIntegrationsJenkins`

Set Jenkins integration.

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

