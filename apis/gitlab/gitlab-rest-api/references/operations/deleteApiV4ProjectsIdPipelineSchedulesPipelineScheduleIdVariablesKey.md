# DELETE /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/variables/{key}

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Delete a pipeline schedule variable**
**Operation ID:** `deleteApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |
| `key` | path | string | Yes | The key of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

