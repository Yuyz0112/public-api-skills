# GET /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/variables/{key}

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Get a single pipeline schedule variable**
**Operation ID:** `getApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |
| `key` | path | string | Yes | The key of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

