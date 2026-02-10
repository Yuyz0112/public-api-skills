# PUT /api/v4/projects/{id}/integrations/pumble

**Resource:** [Integrations](../resources/Integrations.md)
**Create/Edit Pumble integration**
**Operation ID:** `putApiV4ProjectsIdIntegrationsPumble`

Set Pumble integration.

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

