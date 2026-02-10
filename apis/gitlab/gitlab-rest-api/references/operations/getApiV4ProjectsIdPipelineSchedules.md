# GET /api/v4/projects/{id}/pipeline_schedules

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Get all pipeline schedules**
**Operation ID:** `getApiV4ProjectsIdPipelineSchedules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `scope` | query | enum: active, inactive | No | The scope of pipeline schedules |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineSchedule](../schemas/APIEntitiesCiPipelineSchedule/APIEntitiesCiPipelineSchedule.md)

