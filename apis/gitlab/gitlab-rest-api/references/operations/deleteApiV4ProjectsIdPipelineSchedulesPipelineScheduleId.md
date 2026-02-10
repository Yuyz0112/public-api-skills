# DELETE /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Delete a pipeline schedule**
**Operation ID:** `deleteApiV4ProjectsIdPipelineSchedulesPipelineScheduleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 412 | Precondition Failed |

