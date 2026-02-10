# PUT /api/v4/projects/{id}/integrations/custom-issue-tracker

**Resource:** [Integrations](../resources/Integrations.md)
**Create/Edit Custom Issue Tracker integration**
**Operation ID:** `putApiV4ProjectsIdIntegrationsCustomIssueTracker`

Set Custom Issue Tracker integration.

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

