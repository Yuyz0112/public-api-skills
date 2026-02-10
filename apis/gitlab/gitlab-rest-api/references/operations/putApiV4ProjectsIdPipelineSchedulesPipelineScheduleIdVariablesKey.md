# PUT /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/variables/{key}

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Edit a pipeline schedule variable**
**Operation ID:** `putApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |
| `key` | path | string | Yes | The key of the variable |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

