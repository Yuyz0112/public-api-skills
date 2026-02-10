# GET /api/v4/projects/{id}/statistics

**Resource:** [Projects](../resources/Projects.md)
**Get the list of project fetch statistics for the last 30 days**
**Operation ID:** `getApiV4ProjectsIdStatistics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |

**Success Response Schema:**

[APIEntitiesProjectDailyStatistics](../schemas/APIEntitiesProjectDailyStatistics/APIEntitiesProjectDailyStatistics.md)

